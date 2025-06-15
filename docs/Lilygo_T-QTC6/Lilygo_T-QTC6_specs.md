# Lilygo T-QT C6 v1.2 Specifications

T-QT C6 is a mini development board based on the ESP32C6 chip, which is only the size of two thumbnails.

It features a 128x128px TFT full-color touch screen, a separate charging indicator light, and an independent battery.

It can communicate with the power path management chip to modify the power bus status and limit values.


## MCU
- Espressif Systems ESP32-C6-MINI-1U

## SoC
- ESP32-C6-FH4 32-bit RISC-V microprocessor up to 160 MHz
- 320KB ROM
- 512KB HP SRAM
- 16KB LP SRAM
- 4MB flash

## Memory
- 4MB PSRAM (TBC)

## Wireless
- 2.4 GHz WiFi 6 with Target Wake Time (TWT) support
- Bluetooth 5.4 LE and Mesh
- 802.15.4 radio with Zigbee, Thread, and Matter
- IPEX antenna connector

## Display
- 0.85-inch TFT LCD display with 128×128 resolution through GC9107 SPI driver
- Driver Chip: SGM41562
- Communication Protocol: SPI
- capacitive touchscreen via CST816T I2C chip

## USB
- 1x USB-C port for power and programming

## Expansion
- 8-pin female connector with 5x GPIO, 5V. 3.3V, GND
- 4-pin Qwiic UART connector (3.3V)

## Misc
- On/Off switch
- Reset and Boot buttons
- Breathing light (LED connected to IO09)
- LSM6DSLTR 6-axis motion sensor

## Power Management
- Driver Chip: ETA4662
- Communication Protocol: I2C
- 5V/500mA via USB-C port
- SGM41562 I2C PMIC
- Battery level detection through ADC pin
- Consumption – As low as 100uA in deep sleep mode

## Dimensions
- 29 x 24 x 15mm
- M1.4 mounting thread (TBC)


# Relevant libraries
- Arduino_DriveBus v1.1.10
- Arduino_GFX v1.3.7
- LVGL v8.3.5 - Light and Versatile Graphics Library
- Custom library "Mylibrary" with `pin_config.h` (file provided in knowledge base as markdown file)


# Firmware BIN files
- [TQT-C6_V1.0-V1.2][Deep_Sleep]_firmware_V1.0.0.bin
- [TQT-C6_V1.0-V1.2][Light_Sleep]_firmware_V1.0.0.bin
- [TQT-C6_V1.2][Lvgl_CIT_SGM41562]_firmware_V1.0.1.bin


# External tools
- Image2Lcd
- Flash Download Tool v3.9.7

