# Keyboard Core

## Overview
I've made a few custom macro pads, but I decided to start work on my first fully custom mechanical keyboard. Most people use an Arduino Pro Micro for this, but the Pro Micro has a lot of limitations and design choices that don't make it ideal for keyboards. So, I made my own; The Keyboard Core!

The Keyboard Core is still built around the AtMega32u4, allowing it to run Arduino or QMK firmware. In addition, it has a ton of added benefits;

USB-C port instead of MicroUSB, which is also angled off one side of the board, making for more compact mounting above the function keys.

All pins are broken out to one side for easier routing of the main keyboard PCB, with some more pins than the Pro Micro, such as the GPIO usually used for the RX and TX LEDs, which can now be used to add more keys or additional features.

Self-healing polyfuse protects against short-circuits and overcurrent damage to the USB power rail.

Removal of components unneeded for keyboards, such as the voltage regulator circuitry.

All components except the MCU and USB-C are 0805 or larger, allowing for easy repair and modification in the future.

The Keyboard Core also keeps a lot of the good features of the Pro Micro, such as the small footprint and no parts on the bottom of the board, allowing for flush mounting.

## Photos & Media
![3jzximr42ye71](https://user-images.githubusercontent.com/20119374/129489956-8a03f242-726f-4e3c-885b-f7a7023d195c.jpg)

## Current Release
No stable release available. 

## Current State
The Keyboard Core is active, and is currently being developed to version 1.1.

## Support Me
You can purchase the Voltmeter Soldering Kit on [Tindie](https://www.tindie.com/products/jimheaney/voltmeter-soldering-kit/).

You can also buy me a coffee [here](https://www.buymeacoffee.com/jimheaney)!

## License
This project is licensed under the Creative Commons 4.0 Attribution-NonCommercial-ShareAlike. For more information, click [here](https://creativecommons.org/licenses/by-nc-sa/4.0/).

If you want to use this project under a different license, please contact me. 
