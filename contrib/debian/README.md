
Debian
====================
This directory contains files used to package latcoind/latcoin-qt
for Debian-based Linux systems. If you compile latcoind/latcoin-qt yourself, there are some useful files here.

## latcoin: URI support ##


latcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install latcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your latcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/latcoin128.png` to `/usr/share/pixmaps`

latcoin-qt.protocol (KDE)

