iDuos Kernel Custom Kernel For Galaxy Y Duos........

Kernel Dev:manoranjan2050@xda
Connect With Me:http://facebook.com/manoranjan2050
Gtalk:manoranjan2050@gmail.com
My Website:http://manoranjan2050.org

1. How to Build
	- get Toolchain
	Visit http://www.codesourcery.com/, download and install Sourcery G++ Lite 2009q3-68 toolchain for ARM EABI.
	Extract kernel source and move into the top directory.
	$ cd common/
	$ make bcm21553_torino_02_defconfig
	$ make

2. Output files
	- Kernel : kernel/common/arch/arm/boot/zImage
	
3. How to make .tar binary for downloading into target.
	- change current directory to kernel/common/arch/arm/boot
	- type following command
	$ tar cvf GT-S6102_Kernel_Gingerbread.tar zImage
