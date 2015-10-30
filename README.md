# LGG3
SkyDragon Kernel for Lollipop G3

To Buiild:

Check Makefile to verify toolchain location in CROSS_COMPILE

In terminal:
make sd-vzw_defconfig
time make zImage

run dtb tool:
./dtbToolCM -s 2048 -o arch/arm/boot/dt.img -p scripts/dtc/ arch/arm/boot/

grab dt.img in root of source and zImage file in arch/arm/boot and package into your boot.img
bump
flash
??????
profit
