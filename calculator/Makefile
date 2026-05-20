.PHONY: all clean

all: calculator

calculator: main.c addition.c subtraction.c multiplication.c division.c operations.h
	gcc -Wall -Wextra -std=c99 -pedantic main.c addition.c subtraction.c multiplication.c division.c -o calculator

clean:
	rm -f calculator *.o
