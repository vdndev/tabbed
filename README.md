# tabbed - generic tabbed interface

tabbed is a simple tabbed X window container.

## Added Patches
- [Bar Height][1]
- [Client Number][2]
- [Hide Tabs][3]
- [Key Release][4]

## Requirements
------------
In order to build tabbed you need the Xlib header files.

## Installation
------------
Edit config.mk to match your local setup (tabbed is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install tabbed
(if necessary as root):

    make clean install

## Running tabbed
--------------
See the man page for details.

[1]: https://tools.suckless.org/tabbed/patches/barheight/
[2]: https://tools.suckless.org/tabbed/patches/clientnumber/
[3]: https://tools.suckless.org/tabbed/patches/hidetabs/
[4]: https://tools.suckless.org/tabbed/patches/keyrelease/

