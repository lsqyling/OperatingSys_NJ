
a.out: minimal.S
	gcc -S minimal.S > minimal.s
	as minimal.s -o minimal.o
	ld minimal.o

gcc-demo:
	strace -f gcc hello.c

clean:
	rm *.out *.o *.s

