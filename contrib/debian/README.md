
Debian
====================
This directory contains files used to package enzod/enzo-qt
for Debian-based Linux systems. If you compile enzod/enzo-qt yourself, there are some useful files here.

## enzo: URI support ##


enzo-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install enzo-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your enzo-qt binary to `/usr/bin`
and the `../../share/pixmaps/enzo128.png` to `/usr/share/pixmaps`

enzo-qt.protocol (KDE)

