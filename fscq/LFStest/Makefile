CC=gcc
CFLAGS=-Wall -g -pie -fPIC

all: largefile smallfile  write1

largefile: largefile.c stats.c
	$(CC) $(CFLAGS) -o largefile largefile.c stats.c

smallfile: smallfile.c stats.c
	$(CC) $(CFLAGS) -o smallfile smallfile.c stats.c

write1: write1.c stats.c
	$(CC) $(CFLAGS) -o write1 write1.c stats.c


clean:
	rm -rf largefile smallfile  write1
