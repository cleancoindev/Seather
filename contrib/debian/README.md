
Debian
====================
This directory contains files used to package seatherd/seather-qt
for Debian-based Linux systems. If you compile seatherd/seather-qt yourself, there are some useful files here.

## seather: URI support ##


seather-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install seather-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your seatherqt binary to `/usr/bin`
and the `../../share/pixmaps/seather128.png` to `/usr/share/pixmaps`

seather-qt.protocol (KDE)

