
Debian
====================
This directory contains files used to package traffd/traff-qt
for Debian-based Linux systems. If you compile traffd/traff-qt yourself, there are some useful files here.

## traff: URI support ##


traff-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install traff-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your traffqt binary to `/usr/bin`
and the `../../share/pixmaps/traff128.png` to `/usr/share/pixmaps`

traff-qt.protocol (KDE)

