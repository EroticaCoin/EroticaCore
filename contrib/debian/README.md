
Debian
====================
This directory contains files used to package eroticad/erotica-qt
for Debian-based Linux systems. If you compile eroticad/erotica-qt yourself, there are some useful files here.

## erotica: URI support ##


erotica-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install erotica-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your eroticaqt binary to `/usr/bin`
and the `../../share/pixmaps/erotica128.png` to `/usr/share/pixmaps`

erotica-qt.protocol (KDE)

