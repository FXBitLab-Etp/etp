
Debian
====================
This directory contains files used to package etpd/etp-qt
for Debian-based Linux systems. If you compile etpd/etp-qt yourself, there are some useful files here.

## etp: URI support ##


etp-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install etp-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your etp-qt binary to `/usr/bin`
and the `../../share/pixmaps/etp128.png` to `/usr/share/pixmaps`

etp-qt.protocol (KDE)

