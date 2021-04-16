# MS5540C-sensor-example
MS5540C Miniature Barometer Module platformio example.  
Works with esp8266 and Arduino Uno.  
Once the calibration words have been read from the sensor they can also be hardcoded into the programm.  
The MCLK Pin(MCLK_PIN) needs to be set in the programm according to your wiring.

## Wiring examples:
DIN from sensor -> MOSI  
DOUT from sensor -> MISO  
  
### Arduino Uno:
- MOSI: GPIO 11
- MISO: GPIO 12
- SCLK: GPIO 13
- MCLK: GPIO 9

### ESP8266 12-E NodeMCU:
- MOSI: GPIO 13 (D7)
- MISO: GPIO 12 (D6)
- SCLK: GPIO 14 (D5)
- MCLK: GPIO 4  (D2)
