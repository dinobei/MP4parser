AUTOMAKE_OPTIONS=foreign

GDB_CFLAGS= -g -O0

COMMON_CFLAGS=    -std=c99 $(GDB_CFLAGS) 

bin_PROGRAMS=mp4parser

mp4parser_SOURCES=mp4.c  mp4parser.c  stream.c
mp4parser_CFLAGS= $(COMMON_CFLAGS) -I$(top_srcdir)/include  -I$(top_srcdir)
mp4parser_LDFLAGS=-lm


