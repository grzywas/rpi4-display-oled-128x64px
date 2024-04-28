OLED 1.3" 128x64px OLED display HAT for Raspberry Pi

Description:
Device driver for OLED display for Raspberry Pi, 1.3inch diagonal, 128x64 pixels, with embedded controller SH1106, 
communicating via SPI or I2C interface.
Optional interfaces: 4-wire SPI (factory default), 3-wire SPI, I2C, configured via onboard resistor.
1x joystick (5-position), 3x pushbuttons.

Links:
https://www.waveshare.com/product/displays/oled/1.3inch-oled-hat.htm
https://www.waveshare.com/wiki/1.3inch_OLED_HAT

Interface:
SYMBOL			RASPBERRY PI PIN (BCM)	DESCRIPTION
KEY1			P21						Button 1/GPIO
KEY2			P20						Button 2/GPIO
KEY3			P16						Button 3/GPIO
Joystick Up		P6						
Joystick Down	P19						
Joystick Left	P5						
Joystick Right	P26						
Joystick Press	P13
SCLK			P11/SCLK
MOSI			P10/MOSI
DC				P24						Data/Command selection (high for data, low for command)
CS				P8/CE0					Chip selection, low active
RST				P25						Reset, low active

Build instructions:
1. cmake -B build -S .
2. cmake --build ./build
