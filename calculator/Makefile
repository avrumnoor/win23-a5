calculator: main.o addition.o subtraction.o division.o multiplication.o
	cc -o calculator main.o addition.o subtraction.o division.o multiplication.o

main:

addition.o: operations.h

subtraction.o: operations.h

division.o: operations.h

multiplication.o: operations.h

clean:
	rm -rf *.o
	make

.PHONY: clean


