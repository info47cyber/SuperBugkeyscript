# SuperBugkeyscript
The SuperBugKey ATMEGA32U4 BadUSB Development Board features a 32U4 microcontroller, 32KB flash memory, 2.5KB SRAM, and USB 2.0 support. It offers 26 digital I/O pins, 12 analog inputs, and 7 PWM outputs, with a 16 MHz clock. Ideal for USB prototyping and Arduino projects, it enables easy development with built-in USB communication and 5V power.
# Arduino HID Tab Closer

⚠️ **Warning:** This script is for educational purposes only. Use only on devices you own with proper authorization.

## Description
This Arduino sketch (when used with a Leonardo, Micro, or other HID-capable Arduino) creates a VBScript that continuously sends Ctrl+W keypresses to the host computer.

## Requirements
- Arduino Leonardo, Micro, or compatible
- Arduino IDE
- [phukdlib_leonardo.h](https://github.com/Phukd2/Phukd2)

## Installation
1. Clone this repository
2. Open `TabCloser.ino` in Arduino IDE
3. Install the required library
4. Upload to your Arduino

## Usage
After uploading, when connected to a computer, the Arduino will:
1. Open Command Prompt
2. Create a VBScript in Downloads folder
3. Execute the script

## Disclaimer
This is for educational purposes only. Unauthorized use on others' computers is illegal.
