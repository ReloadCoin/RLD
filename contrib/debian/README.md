
Debian
====================
This directory contains files used to package rldd/rld-qt
for Debian-based Linux systems. If you compile rldd/rld-qt yourself, there are some useful files here.

## rld: URI support ##


rld-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install rld-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your rldqt binary to `/usr/bin`
and the `../../share/pixmaps/rld128.png` to `/usr/share/pixmaps`

rld-qt.protocol (KDE)

