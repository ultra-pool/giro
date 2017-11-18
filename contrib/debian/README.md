
Debian
====================
This directory contains files used to package girod/giro-qt
for Debian-based Linux systems. If you compile girod/giro-qt yourself, there are some useful files here.

## giro: URI support ##


giro-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install giro-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your giroqt binary to `/usr/bin`
and the `../../share/pixmaps/giro128.png` to `/usr/share/pixmaps`

giro-qt.protocol (KDE)

