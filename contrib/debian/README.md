
Debian
====================
This directory contains files used to package bogcoind/bogcoin-qt
for Debian-based Linux systems. If you compile bogcoind/bogcoin-qt yourself, there are some useful files here.

## bogcoin: URI support ##


bogcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bogcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bogcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/bogcoin128.png` to `/usr/share/pixmaps`

bogcoin-qt.protocol (KDE)

