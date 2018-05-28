
Debian
====================
This directory contains files used to package atecd/atec-qt
for Debian-based Linux systems. If you compile atecd/atec-qt yourself, there are some useful files here.

## atec: URI support ##


atec-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install atec-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your atecqt binary to `/usr/bin`
and the `../../share/pixmaps/atec128.png` to `/usr/share/pixmaps`

atec-qt.protocol (KDE)

