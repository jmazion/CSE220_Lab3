#!/bin/bash
# File: Makefile
# Daniel Martin and Joshua Mazion


lister: main.o print.o scanner.o
	gcc main.o print.o scanne.o -o lister
	rm *.o

main.o: main.c common.h
print.o: print.c print.h common.h	
scanner.o: scanner.c scanner.h common.h
