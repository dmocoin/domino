
Debian
====================
This directory contains files used to package dominod/domino-qt
for Debian-based Linux systems. If you compile dominod/domino-qt yourself, there are some useful files here.

## domino: URI support ##


domino-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install domino-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dominoqt binary to `/usr/bin`
and the `../../share/pixmaps/domino128.png` to `/usr/share/pixmaps`

domino-qt.protocol (KDE)

