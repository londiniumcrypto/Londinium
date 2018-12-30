
Debian
====================
This directory contains files used to package londiniumd/londinium-qt
for Debian-based Linux systems. If you compile londiniumd/londinium-qt yourself, there are some useful files here.

## londinium: URI support ##


londinium-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install londinium-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your londiniumqt binary to `/usr/bin`
and the `../../share/pixmaps/londinium128.png` to `/usr/share/pixmaps`

londinium-qt.protocol (KDE)

