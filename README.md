NCSA Mosaic
===========

![Wikipedia viewed with Mosaic](https://github.com/downloads/wtachi/ncsa-mosaic/wikipedia-screenshot.png "Wikipedia viewed with Mosaic")

This is [NCSA Mosaic](https://en.wikipedia.org/wiki/Mosaic_(web_browser)), one
of the first graphical web browsers. This version has barely been modified
since the last official release, version 2.7 beta 6, in 1996. You may also be
interested in [Mosaic-CK](http://www.floodgap.com/retrotech/machten/mosaic/)
and [VMS Mosaic](http://wvnvms.wvnet.edu/vmswww/vms_mosaic.html), which have
been substantially improved from the original.

If you're on Linux, your time machine is fueled up and ready to go! Follow the
instructions below to build and run.

Many thanks to [Sean MacLennan and Alan Wylie](http://seanm.ca/mosaic/) for
doing the heavy lifting. And, of course, hats off to Marc Andreessen, Eric
Bina, and the rest of the [NCSA](http://www.ncsa.illinois.edu/) team for
kicking things off for us. Thanks!

[Alan Dipert](http://alan.dipert.org/) took the last release of Mosaic, put it
on Github, and made some fixes. [Tim Pizey](http://pizey.net/~timp/) modified
it so that in-document javascript is not displayed.

Building
--------

On Arch Linux, use the [AUR
package](https://aur.archlinux.org/packages.php?ID=35326).

On Ubuntu:

* First, install these packages:

      sudo apt-get install build-essential libmotif-dev libjpeg62-dev libpng12-dev x11proto-print-dev libxmu-headers libxpm-dev libxmu-dev

* Next, build with:

      make linux

* Run!

      src/Mosaic
