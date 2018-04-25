
Debian
====================
This directory contains files used to package ucomd/ucom-qt
for Debian-based Linux systems. If you compile ucomd/ucom-qt yourself, there are some useful files here.

## ucom: URI support ##


ucom-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ucom-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ucom-qt binary to `/usr/bin`
and the `../../share/pixmaps/ucom128.png` to `/usr/share/pixmaps`

ucom-qt.protocol (KDE)

