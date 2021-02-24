# Arch-on-ESXI-Arm-Fling
__An Installer for installing Arch to ESXI on ARM__

to install you have to get an Ubuntu Server Iso From : https://ubuntu.com/download/server/arm
(we are just using it to install Arch)
once booted (Installer Shows up) up press CTRL + ALT + F2 or CTRL + ALT + F3
a terminal shuld pop up now.
i recommend partitioning your drive first with: sudo cfdisk /dev/sdX

Wget the script with: 
wget (URL Will be here Later)
chmod +x arch-setup.sh
./arch-setup.sh


Notes: 
The Rootfs comes from http://os.archlinuxarm.org/os/ArchLinuxARM-aarch64-latest.tar.gz
Its Possible to Port the installer to x86 and the rapberry pi (maybe ill do that later)
