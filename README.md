# GarageDoorServerInit
SysV init script for the Raspberry Pi server that controls my garage door.

You need to [disable systemd and install the SysV init scripts.]{http://without-systemd.org/wiki/index.php/How_to_remove_systemd_from_a_Debian_jessie/sid_installation}

Copy this script to /etc/init.d and change the "cd" in the "d_start()" fuction to correctly refer to where you installed the server via NetBeans.

This will start the server at boot, shut it down properly and shutdown, and let you do things like "service garagedoor restart"
