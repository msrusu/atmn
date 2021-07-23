
Debian
====================
This directory contains files used to package antimonyd/antimony-qt
for Debian-based Linux systems. If you compile antimonyd/antimony-qt yourself, there are some useful files here.

## antimony: URI support ##


antimony-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install antimony-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your antimonyqt binary to `/usr/bin`
and the `../../share/pixmaps/antimony128.png` to `/usr/share/pixmaps`

antimony-qt.protocol (KDE)

