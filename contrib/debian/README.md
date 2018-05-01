
Debian
====================
This directory contains files used to package pmcd/pmc-qt
for Debian-based Linux systems. If you compile pmcd/pmc-qt yourself, there are some useful files here.

## pmc: URI support ##


pmc-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install pmc-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your pmc-qt binary to `/usr/bin`
and the `../../share/pixmaps/pmc128.png` to `/usr/share/pixmaps`

pmc-qt.protocol (KDE)

