NCSA Mosaic
===========

![Wikipedia viewed with Mosaic](https://github.com/downloads/yotann/ncsa-mosaic/wikipedia-screenshot.png "Wikipedia viewed with Mosaic")

This is [NCSA Mosaic](https://en.wikipedia.org/wiki/Mosaic_(web_browser)), one
of the first graphical web browsers. This version has barely been modified
since the last official release, version 2.7 beta 6, in 1996. You may also be
interested in [Mosaic-CK](http://www.floodgap.com/retrotech/machten/mosaic/)
and [VMS Mosaic](https://web.archive.org/web/20070911192043/http://www.openvms.org/stories.php?story=07%2F09%2F03%2F1740114), which have
been substantially improved from the original.

If you're on Linux, your time machine is fueled up and ready to go! Follow the
instructions below to build and run.

Many thanks to [Sean MacLennan and Alan Wylie](https://web.archive.org/web/20120915154245/seanm.ca/mosaic/) for
doing the heavy lifting. And, of course, hats off to Marc Andreessen, Eric
Bina, and the rest of the [NCSA](http://www.ncsa.illinois.edu/) team for
kicking things off for us. Thanks!

[Alan Dipert](https://github.com/alandipert) took the last release of Mosaic, put it
on Github, and made some fixes. [Tim Pizey](http://pizey.net/~timp/) modified
it so that in-document javascript is not displayed.

Building
--------

On Arch Linux, use the [AUR
package](https://aur.archlinux.org/packages/ncsa-mosaic-git/).

On Ubuntu:

* First, install these packages:

      sudo apt-get install build-essential libmotif-dev libjpeg62-dev libpng12-dev x11proto-print-dev libxmu-headers libxpm-dev libxmu-dev

* Next, build with:

      make linux

* Run!

      src/Mosaic
