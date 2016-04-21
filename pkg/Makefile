obj-m += greedy-iosched.o

default:
	$(MAKE) -C /usr/src/linux M=$(PWD) 

install:
	cp greedy-iosched.o /usr/src/linux/block/


clean:
	-rm *.ko
	-rm *.o
	-rm *.mod.c
	-rm *.out
