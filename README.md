# checkbashisms for Atom

This Atom plugin runs the `checkbashisms` script as a linter on shell scripts.

Bashisms are constructs often found in shell scripts that are only guaranteed to work on bash and other bash-like shells. You should avoid them, because they might not do what you expect on all shells.

## How does it look?

![](https://raw.githubusercontent.com/simonwhitaker/atom-checkbashisms/master/screenshot.png)

## Prerequisites

You'll need a copy of `checkbashisms` installed on your `$PATH`. You can also
manually set the path in Atom's settings.

On Debian-style Linuxes:

    apt-get install devscripts

On Mac OS X:

    brew install checkbashisms
