eclipse2abs
===========

A simple perl script to create an archlinux package from an eclipse update site.

Usage
-----
- install eclipse2abs from [AUR](http://aur.archlinux.org/).
- copy PKGBUILD.tmpl from /usr/share/doc/eclipse2abs and customize it to your needs
- run eclipse2abs \<templatefile\> \<updatesite\>
- a PKGBUILD file is created in the working directory

### Notes:
- <templatefile> is the file that you have customized
- <updatesite> is the URL of the eclipse update site (without site.xml)
