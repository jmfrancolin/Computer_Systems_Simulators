M := rm -f
CC := gcc
CFLAGS := -g
LDLIBS := -lm

cachesim: main.o cachesim.o

cachesim.o: cachesim.c cachesim.h
main.o: main.c cachesim.h

clean:
	rm -f *.o *~ \#* cachesim
