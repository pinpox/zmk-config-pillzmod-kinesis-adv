# Pillzmod Kinesis

This repository is used to generate the [ZMK](https://zmk.dev) firmware for the [Pillz Mod Kinesis Advantage Shield](https://github.com/dcpedit/pillzmod) supporting both the Blackpill USB MCU board and the Pillbug USB/Bluetooth MCU board.

## Keyboard Support

The Pillzmod ZMK shield supports the [Kinesis Advantage](https://kinesis-ergo.com/support/advantage/) MPC USB and the MPC USB/LF.

The default overlay supports the factory default keyboard layout which is 'US International'.

The keyboard layout under Linux is the 'English (US, intl., AltGr Unicode combining)'


## Firmware

The following firmware images are built using the ZMK github build actions.

- Blackpill F401CC
- Blackpill F401CE
- Blackpill F411CE
- Pillbug
- Pillbug Settings Reset

> **Note**: The 'Pillbug Settings Reset' image is used when having problems with the bluetooth system, see ZMK documentation [connection issues](https://zmk.dev/docs/troubleshooting/connection-issues) for more information.