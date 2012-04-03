eclipse2abs
===========

A simple perl script to create an archlinux package for an eclipse plugin from its update site.
This script will not work for the eclipse platform itself.

Usage
-----
- install eclipse2abs from [AUR](http://aur.archlinux.org/).
- copy PKGBUILD.tmpl from /usr/share/doc/eclipse2abs and customize it to your needs
- run eclipse2abs \<templatefile\> \<updatesite\>
- a PKGBUILD file is created in the working directory

### Notes:
- \<templatefile\> is the file that you have customized
- \<updatesite\> is the URL of the eclipse update site (without site.xml)
