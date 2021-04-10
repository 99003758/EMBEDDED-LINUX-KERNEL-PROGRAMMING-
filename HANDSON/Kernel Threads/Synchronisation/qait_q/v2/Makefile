obj-m += wait2.o
KSRC = /home/user/workspace/Package/linux-4.14.202
all:
	make -C ${KSRC} M=${PWD} modules ARCH=arm CROSS_COMPILE=arm-linux-gnueabi-
clean:
	make -C ${KSRC} M=${pwd} clean
