# amarok_sleepy

This repository provides a script for **amarok music player** enabling "screen turn off" and "system shutdown". This script is based on the [original sleepy script](https://www.linux-apps.com/p/1135851); however, it works with advanced linux kernels and is tested with Fedora 33~38 on Dell Inspiron 7373.

In order to use this script, 1) install 'xset' package; 2) set your default login screen to “Xorg” by editing "/etc/gdm/custom.conf" as root user and set "WaylandEnable=false".
