
obj-m += hello2.o
all:
    make -C /home/user/workspace/Package/linux-4.14.202 M=$(PWD) modules ARCH=arm CROSS_COMPILE=arm-linux-gnueabi-
clean:
    make -C /home/user/workspace/Package/linux-4.14.202 M=$(PWD) clean ARCH=arm CROSS_COMPILE=arm-linux-gnueabi-
build:
    arm-linux-gnueabi-gcc my_sys.c -o lio
