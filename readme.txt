INSTEAD LAUNCHER 0.8.0
======================

WARNING! For successfull building you must install qt5.

0) Prepare for building
=======================

Unpack source package with this command:
	$ tar xzvf instead-launcher-qt5_<version>.tar.gz

Change current dir to project's build dir:
	$ cd instead-launcher-qt5_<version>

There are several ways to build package.

1) Native qt build
====================================================
	$ qmake PRREFIX=/usr/local/ or qmake PRREFIX=/usr/
	$ make
	$ make install

2) Easy build
==========================
Try run: 
	$ ./build.sh

Enjoy.
