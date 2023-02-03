# amarok_sleepy

A script for **amarok music player** providing "screen turn off" and "system shutdown", which is based on the original sleepy script.

This script works with advanced linux kernels and is tested with Fedora 33~36 on Dell Inspiron 7373.

In order to use this script, 1) install 'xset' package; 2) set your default login screen to “Xorg” by editing "/etc/gdm/custom.conf" as root user and set "WaylandEnable=false".
