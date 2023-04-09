## Work in progress 
### This i my project to create floor heating in Home Assistant, using

- ESP32 Relay X8 Board [link](https://www.aliexpress.com/item/1005004770320570.html?pdp_npi=2%40dis%21USD%21US%24%2022.59%21US%24%2014.91%21%21%21%21%21%402101c80016810569657425775e0e5e%2112000030409064244%21btf&_t=pvid:e9ef5b4f-4ade-43a5-88ac-7a6e31184b40&afTraceInfo=1005004770320570__pc__pcBridgePPC__xxxxxx__1681056966&spm=a2g0o.ppclist.product.mainProduct)
- SSD1306 128x64 display [link](https://www.aliexpress.com/item/32864585825.html?pdp_npi=2%40dis%21USD%21US%24%201.51%21US%24%201.49%21%21%21%21%21%402101c80016810571909161713e0e5e%2167223868119%21btf&_t=pvid:5c05cea3-5e85-42df-8329-b9b44f82caa2&afTraceInfo=32864585825__pc__pcBridgePPC__xxxxxx__1681057191&spm=a2g0o.ppclist.product.mainProduct)
- button
- HW-482 5v Relay [link](https://www.aliexpress.com/item/1005004662239693.html?spm=a2g0o.productlist.main.1.60ef6d9ajUqXyI&algo_pvid=391b58e5-6542-4c95-a3ed-27e30d2cfcda&algo_exp_id=391b58e5-6542-4c95-a3ed-27e30d2cfcda-0&pdp_npi=3%40dis%21USD%211.24%211.12%21%21%21%21%21%40211be59e16810572874821956d0761%2112000030020673650%21sea%21DK%21848277083&curPageLogUid=MonEb3jYzPMx)
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
