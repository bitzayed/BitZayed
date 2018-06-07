
Debian
====================
This directory contains files used to package bitzayedd/bitzayed-qt
for Debian-based Linux systems. If you compile bitzayedd/bitzayed-qt yourself, there are some useful files here.

## bitzayed: URI support ##


bitzayed-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitzayed-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitzayedqt binary to `/usr/bin`
and the `../../share/pixmaps/bitzayed128.png` to `/usr/share/pixmaps`

bitzayed-qt.protocol (KDE)

