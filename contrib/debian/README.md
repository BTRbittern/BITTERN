
Debian
====================
This directory contains files used to package bitternd/bittern-qt
for Debian-based Linux systems. If you compile bitternd/bittern-qt yourself, there are some useful files here.

## bittern: URI support ##


bittern-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bittern-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitternqt binary to `/usr/bin`
and the `../../share/pixmaps/bittern128.png` to `/usr/share/pixmaps`

bittern-qt.protocol (KDE)

