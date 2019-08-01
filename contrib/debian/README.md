
Debian
====================
This directory contains files used to package eumsd/eums-qt
for Debian-based Linux systems. If you compile eumsd/eums-qt yourself, there are some useful files here.

## eums: URI support ##


eums-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install eums-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your eumsqt binary to `/usr/bin`
and the `../../share/pixmaps/eums128.png` to `/usr/share/pixmaps`

eums-qt.protocol (KDE)

