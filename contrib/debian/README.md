
Debian
====================
This directory contains files used to package buddied/buddie-qt
for Debian-based Linux systems. If you compile buddied/buddie-qt yourself, there are some useful files here.

## buddie: URI support ##


buddie-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install buddie-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your buddie-qt binary to `/usr/bin`
and the `../../share/pixmaps/buddie128.png` to `/usr/share/pixmaps`

buddie-qt.protocol (KDE)

