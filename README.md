chm2pdf
=======
A Python script that converts a CHM file into a single PDF file.

(c) 2007 Massimo Sandal <devicerandom@gmail.com>

(c) 2007-2008 Chris Karakas <chris@karakas-online.de> and <http://www.karakas-online.de>

Usage:
  `chm2pdf [options] input_filename [output_filename]`

For all options, see
  `chm2pdf --help`

RECOMMENDED READING:
 - http://www.karakas-online.de/forum/viewtopic.php?t=10275
 - http://www.karakas-online.de/forum/viewtopic.php?t=10969

Installation:
 - download the .tar.gz
 - unzip it: "tar -xzvf chm2pdf-a.b.c.tar.gz"
 - enter the newly created directory
 - acquire root privileges
 - type "python setup.py install"

Requires:
 - python
 - chmlib. NOTE: chmlib *must* be configured with ./configure --enable-examples
 - pychm
 - htmldoc
 - BeautifulSoup (optional)

All of these should be in your Linux/Unix distribution repository :)
