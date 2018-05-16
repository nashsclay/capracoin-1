
Debian
====================
This directory contains files used to package capracoind/capracoin-qt
for Debian-based Linux systems. If you compile capracoind/capracoin-qt yourself, there are some useful files here.

## capracoin: URI support ##


capracoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install capracoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your capracoinqt binary to `/usr/bin`
and the `../../share/pixmaps/capracoin128.png` to `/usr/share/pixmaps`

capracoin-qt.protocol (KDE)

