## Work in progress 
### This i my project to create floor heating in Home Assistant, using

- ESP32 Relay X8 Board [link](https://www.aliexpress.com/item/1005004770320570.html?pdp_npi=2%40dis%21USD%21US%24%2022.59%21US%24%2014.91%21%21%21%21%21%402101c80016810569657425775e0e5e%2112000030409064244%21btf&_t=pvid:e9ef5b4f-4ade-43a5-88ac-7a6e31184b40&afTraceInfo=1005004770320570__pc__pcBridgePPC__xxxxxx__1681056966&spm=a2g0o.ppclist.product.mainProduct)
- SSD1306 128x64 display
- button
- Xiaomi Thermometer LYWSD03MMC
  * Using [link](https://pvvx.github.io/ATC_MiThermometer/TelinkMiFlasher.html)
  * Custom firmware 4.2
  * BTHome v1 

![image](https://user-images.githubusercontent.com/45771390/230784137-16c43d47-efa1-48c8-9628-77149b1c4eb9.png)


wiring display

- ESP32 pin 3v3 to display VCC
- ESP32 pin gnd to display GND
- ESP32 pin 21 to display SCL
- ESP32 pin 19 to display SDA

wiring button:
- ESP32 pin 16 to button 
- ESP32 pin GND to button

Wiring relay:
- ESP32 pin 5v to relay +
- ESP32 pin GND to relay -
- ESP32 pin 17 to relay s 
