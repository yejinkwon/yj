AR = ar
OUTPUT = libfuncs.a
FILE = func1.o func2.o
CC = cc

$(OUTPUT) : $(FILE)
	$(AR) rv $(OUTPUT) $(FILE) 
%.o : %.c
	$(CC) -g -c -I../include $<
clean :
	rm -f *.o $(OUTPUT)
