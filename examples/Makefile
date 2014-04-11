test: grammar grammar.c
	./grammar

grammar : grammar.c Makefile
	g++  -O0 -g -Wall grammar.c -o grammar


all :
	gcc -fdump-translation-unit -c *.c

clean : grammar
	rm grammar
