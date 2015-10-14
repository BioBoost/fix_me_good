# The compiler
CC=g++

# Compiler flags
CFLAGS=-Wall
  #  -Wall turns on most, but not all, compiler warnings


runme: clean main.o orc.o
	$(CC) $(CFLAGS) -o runme main.o orc.o

main.o:
	$(CC) $(CFLAGS) -c main.cpp

orc.o:
	$(CC) $(CFLAGS) -c orc.cpp

clean:
	rm -f runme *.o
