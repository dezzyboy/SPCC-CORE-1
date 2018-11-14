
Debian
====================
This directory contains files used to package specialcoind/specialcoin-qt
for Debian-based Linux systems. If you compile specialcoind/specialcoin-qt yourself, there are some useful files here.

## specialcoin: URI support ##


specialcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install specialcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your specialcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/specialcoin128.png` to `/usr/share/pixmaps`

specialcoin-qt.protocol (KDE)

