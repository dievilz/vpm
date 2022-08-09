# vpm-posix - An XBPS package management helper for Void Linux

**vpm-posix** is a simple to use, daily-driver, POSIX-compliant enhancement to the awesome XBPS (X Binary Package System), initially designed as a helper tool for use with Void Linux. Feel free to think "Void Package Management" or something if it helps you remember its name, but please note that it's NOT a "package manager" in the nitpickers understanding of the word - especially vpm shouldn't be confused with XBPS - vpm is just an addon helper tool for XBPS to make your life easier. That's it.

# Screenshots

Screenshot of a (not so) recent (anymore) vpm release:

![alt tag](https://raw.githubusercontent.com/dievilz/vpm-posix/master/screenshots/vpm.png)

Screenshot of vpm in full effect:

![alt tag](https://raw.githubusercontent.com/dievilz/vpm-posix/master/screenshots/vpm2.png)

# Motivation to write vpm
I initially found XBPS to have a steep learning-curve, so I wanted to ease the life of new Void Linux users, and XBPS users in general. Please don't feel afraid to look up the corresponding XBPS commands it translates to, or use vpm --show-translations so you even see the translations already when using vpm help. It has been said that vpm will ease the transition from Debian's APT, and some other user-friendly repository/package-managers.

# ZOMG! PONIES!!111
Rainbows and unicorns, indeed. If you like colorized output, please see the --color=true option, too! All vpm options try to have human readable and easy to remember syntax, no --long-option-with-multiple-complex-words, no need to even prefix arguments with --, vpm just tries to do its best it can to understand the user (there are some command-line-switches, though, see vpm help).

# Dependencies
vpm-posix (contrary to the original version, and to avoid using a bloated shell like Bash), works with any POSIX-compliant shell, which should be installed by default on a new Void Linux system. You also will need git to obtain a clone of the vpm GitHub repository (see "Installation" section, below).

# Installation
Installing vpm should be as easy as following the simple following steps:

1. Install git via xbps-install

        $ xbps-install -S git

2. Clone vpm repository

        $ git clone git@github.com:dievilz/vpm-posix.git

I'm not covering how to put vpm into a place that is in your $PATH as I can't give general UNIX administration support in this README.

# Author
* vpm was written by Armin Jenewein (GitHub: @netzverweigerer) <vpm@m2m.pm> under GNU GPLv3
* vpm-posix was written by Diego Villarreal (@dievilz) <dvn@dievilz.xyz> as a fork of vpm



