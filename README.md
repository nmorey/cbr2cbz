cbr2cbz
=======

CBR to CBZ conversion tool for GNU/Linux


Requirements
------------

* A GNU/Linux distro (sorry, no Windows support)
* The non-free package ``unrar-nonfree`` (check [unrar-nonfree](https://packages.debian.org/source/sid/unrar-nonfree/ "Debian non-free") 

Usage
-----

To convert a single CBR file use this (the script can't handle filenames with spaces):

``./cbr2cbz.py <cbr_filename_without_spaces>``

To convert an entire directory with CBR files in int use:

``cbrfolder2cbz.py <directory>``

The script will put CBZ files in the same directory



Introduction
-------------
CBR files use RAR format, a non-free format. If you use a GPL comics reader i