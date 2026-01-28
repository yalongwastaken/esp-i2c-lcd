# ESP32 I2C and LCD Display

A comprehensive collection of ESP32 I2C communication implementations demonstrating bus scanning and LCD1602 display interfacing using both Arduino and ESP-IDF frameworks.

## Project Structure
```
esp32-i2c-lcd/
├── arduino/
│   ├── i2c-lcd_advanced/
│   └── i2c-lcd_basic/
├── esp-idf/
│   ├── i2c-lcd_advanced/
│   └── i2c-lcd_basic/
├── .gitignore
└── README.md
```

## Development Environment
**Primary Development:** PlatformIO

**Compatibility:**
- **Arduino projects:** Compatible with Arduino IDE
- **ESP-IDF projects:** Compatible with native `idf.py` toolchain

**Hardware Tested:** ESP32-WROOM-32E module

## Hardware Requirements
- ESP32-WROOM-32E development board
- I2C LCD1602 
- Pull-up resistors (2.2kΩ - 4.7kΩ) for I2C bus (if not on module)
- Breadboard and jumper wires
- Optional: Photoresistor or potentiometer (for ADC input in advanced examples)

## Key Features
- **I2C Protocol Implementation:** Master mode communication with non-blocking device scanning
- **LCD Display Control:** LCD1602 interfacing with text rendering and custom characters
- **Multi-Framework Support:** Identical functionality in Arduino and ESP-IDF
- **State Machine Architecture:** Non-blocking operation for responsive system behavior
- **Device Detection:** Automated I2C address scanning (typical LCD addresses: 0x27 or 0x3F)

## Author
Anthony Yalong