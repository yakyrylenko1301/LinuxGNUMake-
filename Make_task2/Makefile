all: main.o src1.o src2.o src3.o
	gcc $? -o main

main.o: main.c
	gcc -c $?

src1.o: src1.mk
	make -f $?

src2.o: src2.mk
	make -f $?

src3.o: src3.mk
	make -f $?

clean:
	rm -rf *.o main