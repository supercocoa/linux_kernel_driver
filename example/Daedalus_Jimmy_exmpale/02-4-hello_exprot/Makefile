obj-m := hello_file1.o hello_file2.o

all:
	make -Wall -C /lib/modules/`uname -r`/build M=`pwd` modules
clean:
	make -C /lib/modules/`uname -r`/build M=`pwd` clean
