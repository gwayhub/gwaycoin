
Debian
====================
This directory contains files used to package gwaycoind/gwaycoin-qt
for Debian-based Linux systems. If you compile gwaycoind/gwaycoin-qt yourself, there are some useful files here.

## gwaycoin: URI support ##


gwaycoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install gwaycoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your gwaycoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/gwaycoin128.png` to `/usr/share/pixmaps`

gwaycoin-qt.protocol (KDE)

