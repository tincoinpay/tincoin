
Debian
====================
This directory contains files used to package tincoind/tincoin-qt
for Debian-based Linux systems. If you compile tincoind/tincoin-qt yourself, there are some useful files here.

## tincoin: URI support ##


tincoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install tincoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your tincoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/tincoin128.png` to `/usr/share/pixmaps`

tincoin-qt.protocol (KDE)

