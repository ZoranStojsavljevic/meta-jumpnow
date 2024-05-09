A meta-layer to collect common changes to upstream recipes and configs

Currently used for the following boards

* Beaglebones (BBB,BBBW, BBG, BBGW)
* Gumstix Duovero
* Raspberry Pi, all flavors, but most testing on RPi4, RPi3 and RPi0-W 
* Odroid-C2 
* Lenovo S10e netbook
* Wandboard
* Xilinx (zynq7)

This layer depends on:

	URI: git://git.yoctoproject.org/poky.git
	branch: scarthgap

	URI: git://git.openembedded.org/meta-openembedded
	branch: scarthgap

	URI: git://git.yoctoproject.org/meta-security.git
	branch: scarthgap

	meta-jumpnow layer maintainer: Scott Ellis <scott@jumpnowtek.com>
	meta-jumpnow layer maintainer: Zoran Stojsavljevic <zoran.stojsavljevic@gmail.com>
