
Debian
====================
This directory contains files used to package xhimerad/xhimera-qt
for Debian-based Linux systems. If you compile xhimerad/xhimera-qt yourself, there are some useful files here.

## xhimera: URI support ##


xhimera-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install xhimera-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your xhimeraqt binary to `/usr/bin`
and the `../../share/pixmaps/xhimera128.png` to `/usr/share/pixmaps`

xhimera-qt.protocol (KDE)

