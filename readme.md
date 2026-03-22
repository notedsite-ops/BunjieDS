# BunjieDS

This is BunjieDS, the open source Nintendo DS web browser that is a derivative of Bunjalloo. The original Bunjalloo was originally
developed by Richard Quirk until 2010. This repository contains a working fork
that you can build with modern BlocksDS.

Bunjalloo was implemented from scratch [using the whatwg user agent design
rules](http://www.whatwg.org/).

This fork of Bunjalloo brings to the table my low-level skills and pure hope-it-works. It does feature optimizations!

BunjieDS can also be built using SDL (the same way Bunjalloo can) so that it's easier to develop it and
debug it.

## Setup

In order to install it in your Nintendo DS or DSi, copy `bunjie.nds` (or whatever you named your built file, if you built it yourself) to your
SD card. The contents of `sdroot` must be copied to the root of your SD card.

## Controls
The controls are inherited and aim to stay the same as Bunjalloo.

- A: Enter a URL.
- B: Reload page.
- Y: Open bookmarks page.
- X: Open settings page.
- L: Move backwards in the history.
- R: Move forwards in the history.
- Up/Down: Scroll screen up and down.
- Left/Right: Scroll screen a page at a time.
- Select: Move toolbar to a different side of the touch screen.
- Click stylus: Follow link, enter data in forms, press keys.
- Hold stylus: Scroll.

## Features

- Slot-2 RAM expansion support (Opera, SuperCard SD, etc).
- Bookmark support.
- Cookie and image support.
- Optional CA certificate checks.

## Credits

- Richard Quirk (quirkysoft):
  - Original author of Bunjalloo (http://code.google.com/p/quirkysoft)

- Antonio Niño Díaz:
  - Port to BlocksDS.
  - Maintainer after version 0.8.0.
