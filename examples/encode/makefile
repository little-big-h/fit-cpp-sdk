CC=g++
CFLAGS=-I"." -I"../../"

encode: encode.o fit_developer_field.o fit_developer_field_definition.o fit_field_base.o fit_protocol_validator.o fit.o fit_buffer_encode.o fit_crc.o fit_date_time.o fit_encode.o fit_field.o fit_field_definition.o fit_mesg.o fit_mesg_definition.o fit_profile.o fit_unicode.o
	$(CC) $(CFLAGS) encode.o fit_developer_field.o fit_developer_field_definition.o fit_field_base.o fit_protocol_validator.o fit.o fit_buffer_encode.o fit_crc.o fit_date_time.o fit_encode.o fit_field.o fit_field_definition.o fit_mesg.o fit_mesg_definition.o fit_profile.o fit_unicode.o -o encode

encode.o: encode.cpp
	$(CC) $(CFLAGS) -c encode.cpp -o encode.o

fit_developer_field.o: ../../fit_developer_field.cpp  
	$(CC) $(CFLAGS) -c ../../fit_developer_field.cpp -o fit_developer_field.o

fit_developer_field_definition.o: ../../fit_developer_field_definition.cpp  
	$(CC) $(CFLAGS) -c ../../fit_developer_field_definition.cpp -o fit_developer_field_definition.o

fit_field_base.o: ../../fit_field_base.cpp  
	$(CC) $(CFLAGS) -c ../../fit_field_base.cpp -o fit_field_base.o

fit_protocol_validator.o: ../../fit_protocol_validator.cpp  
	$(CC) $(CFLAGS) -c ../../fit_protocol_validator.cpp -o fit_protocol_validator.o

fit.o: ../../fit.cpp  
	$(CC) $(CFLAGS) -c ../../fit.cpp -o fit.o

fit_buffer_encode.o: ../../fit_buffer_encode.cpp  
	$(CC) $(CFLAGS) -c ../../fit_buffer_encode.cpp -o fit_buffer_encode.o

fit_crc.o: ../../fit_crc.cpp  
	$(CC) $(CFLAGS) -c ../../fit_crc.cpp -o fit_crc.o

fit_date_time.o: ../../fit_date_time.cpp  
	$(CC) $(CFLAGS) -c ../../fit_date_time.cpp -o fit_date_time.o

fit_encode.o: ../../fit_encode.cpp  
	$(CC) $(CFLAGS) -c ../../fit_encode.cpp -o fit_encode.o

fit_field.o: ../../fit_field.cpp  
	$(CC) $(CFLAGS) -c ../../fit_field.cpp -o fit_field.o

fit_field_definition.o: ../../fit_field_definition.cpp  
	$(CC) $(CFLAGS) -c ../../fit_field_definition.cpp -o fit_field_definition.o

fit_mesg.o: ../../fit_mesg.cpp  
	$(CC) $(CFLAGS) -c ../../fit_mesg.cpp -o fit_mesg.o

fit_mesg_definition.o: ../../fit_mesg_definition.cpp  
	$(CC) $(CFLAGS) -c ../../fit_mesg_definition.cpp -o fit_mesg_definition.o

fit_profile.o: ../../fit_profile.cpp  
	$(CC) $(CFLAGS) -c ../../fit_profile.cpp -o fit_profile.o

fit_unicode.o: ../../fit_unicode.cpp  
	$(CC) $(CFLAGS) -c ../../fit_unicode.cpp -o fit_unicode.o

clean:
	rm -f encode *.o *.fit
