
Debian
====================
This directory contains files used to package foxd/fox-qt
for Debian-based Linux systems. If you compile foxd/fox-qt yourself, there are some useful files here.

## fox: URI support ##


fox-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install fox-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your foxqt binary to `/usr/bin`
and the `../../share/pixmaps/fox128.png` to `/usr/share/pixmaps`

fox-qt.protocol (KDE)

