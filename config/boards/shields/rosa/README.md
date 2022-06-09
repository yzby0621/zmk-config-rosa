# Rosa

The Rosa keyboard is a 54 keys unibody split keyboards that aims to be a good entry point into the ergonomic keyboard world for folks not yet deep into the hobby.
It is minimalistic, excluding such bells and whistles as backlighting, encoders or screens, but should be a good mix of usable, carriable and aesthetically pleasing.

## Features
* Minimal soldering required
  * A `pro-micro` like board
  * A reset button
  * 54 switches and diodes
* Plenty of keys to help new ergo-users along their transition
  * 4x6 + 3 keys per hand
  * Num row
  * Pinky col
  * 3 keys thumb cluster
* Wireless option with `nice!nano v2`
* Compact shape, roughly the same footprint as the magic keyboard from Apple
* Ergonomic key layout
  * Ferris stagger (except for the thumb clusters)
  * 20 degrees tilt angle for each hand

## Default keymap

In the ethos of the Rosa keyboard, the default keymap aims to be relatively easy to pick up for someone coming from a rectangle, while not being "dumbed down".
It should be a great "first keymap" without modification, while also providing a platform for adopting more customizations as the user becomes more familiar
with their hardware.

It is based on [Miryoku](https://github.com/manna-harbour/miryoku/tree/master/docs/reference) as it is a well thought out and well documented keymap
that is as close as it gets to a standard for small keyboard keymaps, with a few notable exceptions:
* QWERTY based
  * We are targeting new users who might not be ready to re-learn all aspects of their keymap at the same time
* No homerow modifiers
  * These can take some getting used to. Use the extra pinky columns for Meta, Ctrl, Alt and R-Alt instead
* No mouse layer
  * I don't think plain ZMK supports that functionality yet, and it might not be something new users expect from their keyboards anyway

## Accessible customization

For users who prefer to edit their keymap through a graphical interface, the firware can be configured using @nickcoutsos' [keymap-editor](https://github.com/nickcoutsos/keymap-editor) tool.
See the readme in [zmk-config-rosa](https://github.com/pierrechevalier83/zmk-config-rosa/) repository for instructions on how to set this up.
