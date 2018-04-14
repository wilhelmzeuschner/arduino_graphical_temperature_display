# Arduino graphical Temperature and Humidity Display

This project is based on an Arduino Nano with ATmega328p.
Temperature and Humidity readings obtained from a DHTxx sensor are displayed on a 84x48 ("5110 Nokia") Display.
In addition to that, a graph of the temperature of the last 60 seconds, 60 minutes or 60 hours will be drawn onto the display.

Two buttons can be used to select which readings are displayed or whether the backlight is: 
_Always ON_, _Always OFF_ or _Adaptive_. A LDR is used for the _Adaptive_-mode.

Certain information, like the selected backlight-mode, will be saved in the internal EEPROM.

Required libaries:
https://github.com/adafruit/Adafruit-GFX-Library,
https://github.com/adafruit/Adafruit-PCD8544-Nokia-5110-LCD-library and
https://github.com/adafruit/DHT-sensor-library
