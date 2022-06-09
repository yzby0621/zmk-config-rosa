# Keymap Editor - Rosa

This is a customization of the ZMK config for the Rosa keyboard with machine
readable layout and keymap definitions for use with @nickcoutsos' [keymap-editor](https://github.com/nickcoutsos/keymap-editor) tool.

![Screenshot](https://i.imgur.com/6Ny3WK8.png)

# Usage

* Navigate to the [keymap-editor](https://nickcoutsos.github.io/keymap-editor/) web app.
* In the `Source` drop-down menu, select GitHub.
* For the repository, input this repository's location: `pierrechevalier83/zmk-config-rosa`
* For the branch, select `main`.
* Modify the keymap as desired.
  * Refer to the [zmk documentation](https://zmk.dev/docs) for a description of the various [behaviours](https://zmk.dev/docs/behaviors/key-press) and [codes](https://zmk.dev/docs/codes).
* Once you're happy with the changes, click "Commit Changes" at the bottom right of the page.
* Give it a few minutes (should be less than 10 minutes) to build the new firmware. There will be a button at the bottom right of the page that you can use to downlad the firmware.
* Download the firmware and extract it somewhere.
* Plug your rosa to your computer and quickly double tap the reset button.
  * The left LED should be flashing blue, indicating the keyboard is in bootloader mode.
  * The keyboard should appear as a new drive on your system, with name: `NICENANO`
* As superuser, copy the `rosa_nice_nano_v2.uf2` file that you extracted from the downloaded zip file to the root of the `NICENANO` drive.
* Type a few letters with the Rosa. It should now be using the updated keymap.

# Usage for other users than yours truly

For the keymap-editor to do its job, it will need write access to the github repo it's pointing at.

If you want to use the keymap-editor for your Rosa keyboard and you are not this repository's author, please fork this repo first and substitute any reference to `pierrechevalier83` in the README with you own username.
