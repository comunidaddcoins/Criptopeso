
Debian
====================
This directory contains files used to package criptopesod/criptopeso-qt
for Debian-based Linux systems. If you compile criptopesod/criptopeso-qt yourself, there are some useful files here.

## criptopeso: URI support ##


criptopeso-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install criptopeso-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your criptopesoqt binary to `/usr/bin`
and the `../../share/pixmaps/criptopeso128.png` to `/usr/share/pixmaps`

criptopeso-qt.protocol (KDE)

