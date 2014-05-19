NAS-NSA325-mod
==============

A set of mods to completely replace Zyxel NSA-325/v2 NAS box firmware.


Recommended read order:

- Get SERIAL ACCESS: http://zyxel.nas-central.org/wiki/Serial_port_(NSA325)

- Get acquainted with the community work:
	- http://forum.doozan.com/read.php?2,14351
	- http://forum.doozan.com/read.php?2,12096
	- http://forum.doozan.com/read.php?3,14697

- rootfs-initramfs/initramfs.txt
	- Compile Initramfs instructions

- rootfs-initramfs/rootfs.txt
	- Build Debian 7.0 that will boot from USB stick

- kernel/kernel-mach.txt
	- Compile Kernel instructions

- install/install-on-usb.txt
	- install rootFS on USB stick

- uboot/stock_u-boot.txt
	- Modify bootloader options to boot from USB
	

ToDO:

- Document HDD integration from hdd-data*,hdd-swap,hdd-scratch
- Integrate Samba config from NAS-DNS325-mod


CREDITS: please see each file the Credits section.