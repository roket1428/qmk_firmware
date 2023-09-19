# retina

![retina](imgur.com image replace me!)

(WIP Desing) An open-source iris inspired split ergo keyboard that you can actually build yourself. It's very similar to the iris keyboard hence the name. Extra effort has been made to make keymaps iris-compatible at the firmware level.

* Keyboard Maintainer: [roket1428](https://github.com/roket1428)
* Hardware Supported: ATmega32u4
* Hardware Availability: digikey.com, mouser.com, aliexpress.com, your local electronics shop, etc.

For the complete build guide check https://bytees.stream/retina.html

Make example for this keyboard (after setting up your build environment):

    make retina:default

Flashing example for this keyboard:

    make retina:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
