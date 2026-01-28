# ESP32 I2C and OLED

A comprehensive collection of ESP32 I2C communication implementations demonstrating bus scanning, device interfacing, and SSD1306 OLED display control with real-time ADC data visualization using both Arduino and ESP-IDF frameworks.

## Project Structure
```
esp32-i2c-oled/
├── arduino/
│   ├── i2c_scanner/
│   └── adc_oled_display/
├── esp-idf/
│   ├── i2c_scanner/
│   └── adc_oled_display/
├── docs/
│   └── day6_complete_module.md
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
- SSD1306 OLED display (128×64, I2C)
- Photoresistor or potentiometer (for ADC input)
- Pull-up resistors (2.2kΩ - 4.7kΩ) for I2C bus (if not on module)
- Breadboard and jumper wires

## Key Features

- **I2C Protocol Implementation:** Master mode communication with device scanning
- **OLED Display Control:** SSD1306 interfacing with graphics and text rendering
- **Multi-Framework Support:** Identical functionality in Arduino and ESP-IDF
- **Real-Time Visualization:** ADC sensor data displayed with numerical and graphical representations
- **Signal Processing:** Moving average filtering for noise reduction

## Author

Anthony Yalong