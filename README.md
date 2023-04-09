### This i my project to create floor heating in Home Assistant, using
- ESP32 Relay X8 Board
- SSD1306 128x64 display
- button
- Xiaomi Thermometer LYWSD03MMC
  * Using [link](https://pvvx.github.io/ATC_MiThermometer/TelinkMiFlasher.html)
  * Custom firmware 4.2
  * BTHome v1 

wiring display

ESP32 pin 3v3 to display VCC
ESP32 pin gnd to display GND
ESP32 pin 21 to display SCL
ESP32 pin 19 to display SDA

wiring button:
ESP32 pin 16 to button 
ESP32 pin GND to button

Wiring relay:
ESP32 pin 5v to relay +
ESP32 pin GND to relay -
ESP32 pin 17 to relay s 
