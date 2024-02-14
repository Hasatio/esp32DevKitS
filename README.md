# ESP32-DEVKIT-S

The circuit taken as an example while designing the board [Thing Plus C - ESP32 WROOM](https://www.sparkfun.com/products/retired/18018)

This pcb scaled down using the components in the example schematic


## Revision 0

### Added:

- 1x ADXL345 (Accelerometer)
- 2x 1x20 FPC connector for ESP pins
- In breakable PCB:
  - 4x ADS1115 (Analog to Digital Converter)
  - 1x20 FPC connector
  - 1x QWIIC connector

### Changed:

- ESP32-WROOM-32D model
- Battery socket breakable PCB
- Logo

### Removed:

- RGB led
- SD card

### Note: The connection cannot be made because the tx rx connection paths are not correct.


## Revision 1

- Two circuits were produced for the left and right foot.

### Added:
- New circuit in mirror image design

### Changed:
- Circuit design, components in usb communication and components in the power section
- CH340C model
- TX, RX connection paths reversed
- Analog pull up resistor 100k

### Note: The battery does not charge when the switch is in the off position.


## Revision 2


### Changed:
- The on/off switch will only be used for battery discharge
