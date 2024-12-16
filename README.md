# Nick's zmk-config (forked from eigatech via [Ergo Split Keyb Videos](https://www.youtube.com/playlist?list=PL1E2ddJCbc13DvCGYXX9jVVX1BqNGKE5D)) for the Totem


## TOTEM

- [TOTEM](https://github.com/eigatech/zmk-config/tree/totem)
- [TOTEM Dongle](https://github.com/eigatech/zmk-config/tree/totem-dongle)

## ZMK

- [Documentation](https://zmk.dev/docs)

## Dongle Flashing

> [!Tip]  
> Enter bootloader mode by pressing the Reset butting twice within 250 ms for Flashing the firmware

1. Turn all controllers off
2. Flash the dongle controller with the **appropriate** `settings_reset` file.
3. Flash the dongle controller with the `dongle` file. Then disconnect from system.
4. Flash the first half with the the `settings_reset` file. Then disconnect from system.
5. Flash the first half with the `left` or `right` files.
6. Connect dongle and flashed half. Confirm working by typing into a text Editor. Then disconnect both dongle and half.
7. Repeat steps 4, 5, and 6 for the other half.

## Documentation on ZMK and Dongle vs Dongle-less 

https://docs.slicemk.com/firmware/zmk/wireless/dongle/

The default setup currently does not have the &bt Profile functions mapped. 
You welcome to map those functions into a Layer to allow the other devices to connect via Bluetooth to the dongle per notation [here](https://docs.slicemk.com/firmware/zmk/wireless/dongle/#dongle-setup).


## ZMK Keymap Editor

Nick Coutsos' [Keymap Editor](https://nickcoutsos.github.io/keymap-editor/) is a user-friendly, browser-based WYSIWYG app designed to make editing your keymap file easier. It supports conditional layers, behaviors, combo and macro editing, rotary encoders, and more.

This editor was used to create the keymap in this repo. You will need to fork this repo to your own GitHub account to make edits.
