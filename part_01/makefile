CFLAGS=-g -Wall

a.out: logisim.c
	gcc $(CFLAGS) logisim.c


cpu: cpu.c
	gcc -o cpu cpu.c $(CFLAGS)


run: a.out
	./a.out | python seven_seg.py

clean:
	rm -f a.out