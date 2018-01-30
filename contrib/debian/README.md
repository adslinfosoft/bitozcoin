
Debian
====================
This directory contains files used to package bitozd/bitoz-qt
for Debian-based Linux systems. If you compile bitozd/bitoz-qt yourself, there are some useful files here.

## bitoz: URI support ##


bitoz-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitoz-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitoz-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitoz128.png` to `/usr/share/pixmaps`

bitoz-qt.protocol (KDE)

