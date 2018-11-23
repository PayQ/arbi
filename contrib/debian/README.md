
Debian
====================
This directory contains files used to package arbid/arbi-qt
for Debian-based Linux systems. If you compile arbid/arbi-qt yourself, there are some useful files here.

## arbi: URI support ##


arbi-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install arbi-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your arbiqt binary to `/usr/bin`
and the `../../share/pixmaps/arbi128.png` to `/usr/share/pixmaps`

arbi-qt.protocol (KDE)

