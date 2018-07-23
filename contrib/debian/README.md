
Debian
====================
This directory contains files used to package BitcoinAdultd/BitcoinAdult-qt
for Debian-based Linux systems. If you compile BitcoinAdultd/BitcoinAdult-qt yourself, there are some useful files here.

## BitcoinAdult: URI support ##


BitcoinAdult-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install BitcoinAdult-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your BitcoinAdultqt binary to `/usr/bin`
and the `../../share/pixmaps/BitcoinAdult128.png` to `/usr/share/pixmaps`

BitcoinAdult-qt.protocol (KDE)

