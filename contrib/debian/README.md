
Debian
====================
This directory contains files used to package sarmacoinsd/sarmacoins-qt
for Debian-based Linux systems. If you compile sarmacoinsd/sarmacoins-qt yourself, there are some useful files here.

## sarmacoins: URI support ##


sarmacoins-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install sarmacoins-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your sarmacoins-qt binary to `/usr/bin`
and the `../../share/pixmaps/sarmacoins128.png` to `/usr/share/pixmaps`

sarmacoins-qt.protocol (KDE)

