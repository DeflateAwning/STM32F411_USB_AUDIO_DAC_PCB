# STM32F411_USB_AUDIO_DAC_PCB
PCB for USB Audio DAC using STM32F411/401 IC and PCM5102A

This is a simple PCB for the perfboard-and-firmware project created by [har-in-air](https://github.com/har-in-air) at https://github.com/har-in-air/STM32F411_USB_AUDIO_DAC.

This project aims to create a very small, high-quality USB-C DAC, using KiCAD to make the PCB and OpenSCAD to make a simple 3D-printable enclosure. The firmware from the aforementioned project will be used as-is.

Soldering this project may be difficult; take a look at the perfboard option using the STM32 Black Pill and PCM5102A module if soldering small SMD components is outside of your capabilities.

## Bill of Materials (BOM)

* STM32F401CCU6 or STM32F411CEU6 <!-- FIXME: decide on one >
* PCM5102A
* USB-C female port
* Headphone jack

### Passives
1206 parts are used for this project. Yes, I can solder 0805, 0603, and 0402 parts. But I can solder 1206 parts perfectly 100% of the time with no assistive tools, so that's what I use.

* Resistors
* Capacitors
* maybe an inductor for fun

## License
This hardware project (PCB and enclosure) is licensed under the [CERN Open Hardware Licence Version 2 - Permissive](https://choosealicense.com/licenses/cern-ohl-p-2.0/) licence:

> A permissive license for hardware designs, with conditions only requiring preservation of notices. Contributors provide an express grant of patent rights. Licensed works, modifications, and larger works may be distributed under different terms and without sources.
