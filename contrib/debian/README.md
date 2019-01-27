
Debian
====================
This directory contains files used to package blacercoind/blacercoin-qt
for Debian-based Linux systems. If you compile blacercoind/blacercoin-qt yourself, there are some useful files here.

## blacercoin: URI support ##


blacercoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install blacercoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your blacercoinqt binary to `/usr/bin`
and the `../../share/pixmaps/blacercoin128.png` to `/usr/share/pixmaps`

blacercoin-qt.protocol (KDE)

