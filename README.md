sysmatt-rpi-tools
=================

Tools used to clone raspberry pi SD cards and OS images

The following note has been extracted from the Author's original article and is corrected here:

Note for NOOBs Users: 
If you are running a SD card created with NOOBs, you will need to manually modify the boot/cmdline.txt and etc/fstab files on your new SD card before you can boot. You must edit and substitute the mmcblk0p* device names for the proper ones. In the fstab, slash (/) should be /dev/mmcblk0p2 and /boot should be /dev/mmcblk0p1. In the cmdline.txt file, root= part should be root=/dev/mmcblk0p2. Once you have done that the OS that you backed up will be the only OS on the new SD card event if your NOOBs SD had multiple flavors of raspberry pi OS installed.
