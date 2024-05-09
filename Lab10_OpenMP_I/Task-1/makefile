CC = gcc
LD = gcc
CFLAGS = -O0 -Wall -Werror
LDFLAGS = 
RM = /bin/rm -f
OBJS =  hello_openmp.o
EXECUTABLE = hello

all:$(EXECUTABLE)

$(EXECUTABLE): $(OBJS)
	$(LD) $(LDFLAGS) $(OBJS) -o $(EXECUTABLE)

sort_funcs.o:  hello_openmp.c
	$(CC) $(CFLAGS) -c hello_openmp.c


clean:
	$(RM) $(EXECUTABLE) $(OBJS)