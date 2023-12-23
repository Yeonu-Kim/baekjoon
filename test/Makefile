CC = g++-11 --std=c++17
RD = rm -f

main.o: main.cpp main.h
	$(CC) -c main.cpp

main.out: main.o
	$(CC) main.o -o main.out

clean:
	$(RD) *.o
