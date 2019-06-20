
Debian
====================
This directory contains files used to package masterleisurecoind/masterleisurecoin-qt
for Debian-based Linux systems. If you compile masterleisurecoind/masterleisurecoin-qt yourself, there are some useful files here.

## masterleisurecoin: URI support ##


masterleisurecoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install masterleisurecoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your masterleisurecoinqt binary to `/usr/bin`
and the `../../share/pixmaps/masterleisurecoin128.png` to `/usr/share/pixmaps`

masterleisurecoin-qt.protocol (KDE)

