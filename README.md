Enhanced openbox menu editor with icon support

![screenshot](https://github.com/zen0bit/obmenu3/blob/main/1.png "")

From original project:
https://sourceforge.net/projects/obmenu3/

obmenu3 - openbox menu editor
(c) Alexey Korop, 2013, mailto:akorop@ukr.net

Installation (as root)

    * unpack the archive;
    * copy unpacked usr/ to the your /usr/.

  Another metod:
    * stay on the filesystem root (/);
    * unpack the archive.

Unistallation (as root):

  remove the following files:

usr/share/icons/hicolor/16x16/apps/obmenu3.png
usr/share/pixmaps/obmenu3.png
usr/share/applications/obmenu3.desktop
usr/bin/obmenu3

Dependencies

  This program depends on gtk2.

Changelog

1.05
 [+] Menu position support added ("x" and "y" properties as addition
     to the "key" property).
 [+] "Copy" button added.
 [-] Menu insertion degradation fixed.

1.04
 [+] XML-comments support added

1.03
 [+] "key" property support improved for items and menus (see bugzilla openbox,
     bugs 6357,6358). To activate add -k or --key to the commandline.
 [+] added some service for menu referenced by id
 [*] small cosmetic changes

1.02
 internal release

1.01
 [+] XML-specific stuffs added in the XML edit window.
 [*] 'file://' and nonprinted characters are now removed upon the file D&D
     into the input lines from some filemanagers as pcmanfm

1.00 First release
 [-] crash after buggy XML editing
 [+] checkbox "Backup" added
 [*] small cosmetic changes

0.92
 [-] fixes in "Startup notify" checkbox behavior

0.91
 [*] help changed
 [+] "Restore" button added
 [-] crash on void menu fixed
 [*] now gtk2 engine used for icon search
 [+] deleting from the holdbox improved
 [+] now Ins key in the holdbox restore item
 [*] keep "encoding" attribute (custom laz2_xmlwrite, see laz2_xmlwrite.patch)

0.90 initial pre-release

Legend:
 [-] bugfix
 [+] new feature
 [*] insignificant change
