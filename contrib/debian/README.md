
Debian
====================
This directory contains files used to package csignald/csignal-qt
for Debian-based Linux systems. If you compile csignald/csignal-qt yourself, there are some useful files here.

## csignal: URI support ##


csignal-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install csignal-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your csignal-qt binary to `/usr/bin`
and the `../../share/pixmaps/csignal128.png` to `/usr/share/pixmaps`

csignal-qt.protocol (KDE)

