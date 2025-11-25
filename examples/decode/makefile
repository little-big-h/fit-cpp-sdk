CC=g++
CFLAGS=-I"." -I"../../"

decode: decode.o fit_developer_field.o fit_developer_field_definition.o fit_developer_field_description.o fit_field_base.o fit.o fit_accumulated_field.o fit_accumulator.o fit_buffered_mesg_broadcaster.o fit_buffered_record_mesg_broadcaster.o fit_crc.o fit_decode.o fit_field.o fit_field_definition.o fit_mesg.o fit_mesg_broadcaster.o fit_mesg_definition.o fit_mesg_with_event_broadcaster.o fit_profile.o fit_unicode.o
	$(CC) $(CFLAGS) decode.o fit_developer_field.o fit_developer_field_definition.o fit_developer_field_description.o fit_field_base.o fit.o fit_accumulated_field.o fit_accumulator.o fit_buffered_mesg_broadcaster.o fit_buffered_record_mesg_broadcaster.o fit_crc.o fit_decode.o fit_field.o fit_field_definition.o fit_mesg.o fit_mesg_broadcaster.o fit_mesg_definition.o fit_mesg_with_event_broadcaster.o fit_profile.o fit_unicode.o -o decode

decode.o: decode.cpp
	$(CC) $(CFLAGS) -c decode.cpp -o decode.o

fit_developer_field.o: ../../fit_developer_field.cpp
	$(CC) $(CFLAGS) -c ../../fit_developer_field.cpp -o fit_developer_field.o

fit_developer_field_definition.o: ../../fit_developer_field_definition.cpp
	$(CC) $(CFLAGS) -c ../../fit_developer_field_definition.cpp -o fit_developer_field_definition.o

fit_developer_field_description.o: ../../fit_developer_field_description.cpp
	$(CC) $(CFLAGS) -c ../../fit_developer_field_description.cpp -o fit_developer_field_description.o

fit_field_base.o: ../../fit_field_base.cpp
	$(CC) $(CFLAGS) -c ../../fit_field_base.cpp -o fit_field_base.o

fit.o: ../../fit.cpp
	$(CC) $(CFLAGS) -c ../../fit.cpp -o fit.o

fit_accumulated_field.o: ../../fit_accumulated_field.cpp
	$(CC) $(CFLAGS) -c ../../fit_accumulated_field.cpp -o fit_accumulated_field.o

fit_accumulator.o: ../../fit_accumulator.cpp
	$(CC) $(CFLAGS) -c ../../fit_accumulator.cpp -o fit_accumulator.o

fit_buffered_mesg_broadcaster.o: ../../fit_buffered_mesg_broadcaster.cpp
	$(CC) $(CFLAGS) -c ../../fit_buffered_mesg_broadcaster.cpp -o fit_buffered_mesg_broadcaster.o

fit_buffered_record_mesg_broadcaster.o: ../../fit_buffered_record_mesg_broadcaster.cpp
	$(CC) $(CFLAGS) -c ../../fit_buffered_record_mesg_broadcaster.cpp -o fit_buffered_record_mesg_broadcaster.o

fit_crc.o: ../../fit_crc.cpp
	$(CC) $(CFLAGS) -c ../../fit_crc.cpp -o fit_crc.o

fit_decode.o: ../../fit_decode.cpp
	$(CC) $(CFLAGS) -c ../../fit_decode.cpp -o fit_decode.o

fit_field.o: ../../fit_field.cpp
	$(CC) $(CFLAGS) -c ../../fit_field.cpp -o fit_field.o

fit_field_definition.o: ../../fit_field_definition.cpp
	$(CC) $(CFLAGS) -c ../../fit_field_definition.cpp -o fit_field_definition.o

fit_mesg.o: ../../fit_mesg.cpp
	$(CC) $(CFLAGS) -c ../../fit_mesg.cpp -o fit_mesg.o

fit_mesg_broadcaster.o: ../../fit_mesg_broadcaster.cpp
	$(CC) $(CFLAGS) -c ../../fit_mesg_broadcaster.cpp -o fit_mesg_broadcaster.o

fit_mesg_definition.o: ../../fit_mesg_definition.cpp
	$(CC) $(CFLAGS) -c ../../fit_mesg_definition.cpp -o fit_mesg_definition.o

fit_mesg_with_event_broadcaster.o: ../../fit_mesg_with_event_broadcaster.cpp
	$(CC) $(CFLAGS) -c ../../fit_mesg_with_event_broadcaster.cpp -o fit_mesg_with_event_broadcaster.o

fit_profile.o: ../../fit_profile.cpp
	$(CC) $(CFLAGS) -c ../../fit_profile.cpp -o fit_profile.o

fit_unicode.o: ../../fit_unicode.cpp
	$(CC) $(CFLAGS) -c ../../fit_unicode.cpp -o fit_unicode.o

clean:
	rm -f decode *.o
