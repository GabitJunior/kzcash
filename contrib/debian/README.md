
Debian
====================
This directory contains files used to package kzcashd/kzcash-qt
for Debian-based Linux systems. If you compile kzcashd/kzcash-qt yourself, there are some useful files here.

## kzcash: URI support ##


kzcash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install kzcash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your kzcash-qt binary to `/usr/bin`
and the `../../share/pixmaps/kzcash128.png` to `/usr/share/pixmaps`

kzcash-qt.protocol (KDE)

