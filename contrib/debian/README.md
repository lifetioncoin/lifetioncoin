
Debian
====================
This directory contains files used to package lifetioncoind/lifetioncoin-qt
for Debian-based Linux systems. If you compile lifetioncoind/lifetioncoin-qt yourself, there are some useful files here.

## lifetioncoin: URI support ##


lifetioncoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install lifetioncoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your lifetioncoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/lifetioncoin128.png` to `/usr/share/pixmaps`

lifetioncoin-qt.protocol (KDE)

