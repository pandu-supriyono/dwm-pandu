Pandu's fork of DWM
============================
dwm is an extremely fast, small, and dynamic window manager for X.

Patches used
------------
- azerty
- noborder
- pertag
- xrdb
- My own config

I use this build in conjunction with `slstatus`, as well as some nifty dwm-based programs for quick access to Keepass and to the network manager, namely:
- [firecat53/keepmenu](https://github.com/firecat53/keepmenu)
- [firecat53/keepmenu](https://github.com/firecat53/networkmanager-dmenu)

Installation
------------
Enter the following command to build and install dwm (if
necessary as root):

    make clean install

Running dwm
-----------
Add the following line to your .xinitrc to start dwm using startx:

    exec dwm

In order to connect dwm to a specific display, make sure that
the DISPLAY environment variable is set correctly, e.g.:

    DISPLAY=foo.bar:1 exec dwm

(This will start dwm on display :1 of the host foo.bar.)

