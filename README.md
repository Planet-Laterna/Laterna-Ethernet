# Laterna-Ethernet

The Laterna series of boards are mainly intended to be used with [WLED software ](https://github.com/Aircoookie/WLED "WLED's Homepage"), but you can also program the board using your own code or other library via [Arduino](https://www.arduino.cc "Arduino Homepage"), [ESPHome](https://esphome.io "ESPHome Homepage"), [Tasmota](https://tasmota.github.io/docs "Tasmota Homepage") etc.
<br>The board comes with or without soldered screw terminal and extra pins.

The controller can be ordered from [Aliexpress](https://www.aliexpress.com/item/1005003773589994.html?spm=5261.ProductManageOnline.0.0.3aaa4edfzpZkav)<br>

<h3>Features</h3>
Chip: ESP32 WROOM 32E Wifi and Bluetooth
<br>USB Type C connector for flashing / programming only
<br>CH340 USB to serial chip for easy flashing  
<br>4 channels for adressable LED strips 5v and 12V (e.g. WS2812, WS2815, SK6812 etc.)
<br>Each channel can support 10 A and has output overcurrent protection. No external Fuse required
<br>Internal relay to completly control the power for the LED strips 
<br>Onboard INMP441 high-performance digital omnidirectional microphone
<br>Onboard Ethernet
<br>Works with 5V, 12V (Input = Output Voltage)
<br>3 additional GPIOs for adding sensors, buttons, etc.

<br><img src="/Photos/Laterna-V2.jpg" width="50%">

<h3>Installation</h3>

All our boards are delivered with a default WLED version **link to board version and software flashed**.You can use the board out of the box after you solder required connectors.

You can customize the software based on your needs and flash it by **USB** or the **programming connector**.
The board has an integrated CH340 USB to UART bridge so you can flash it without using **any additional hardware**.

For Flashing a precompiled<br> Firmware we recommend [ESPHome Flasher](https://github.com/esphome/esphome-flasher/releases "ESPHome Flasher Releases")

We also have a ESPHome template available which can be easily flashed via [this website](https://planet-laterna.github.io/Laterna-ESPHome-template)

<h5>Required steps for manual flashing</h5>

* First you need to put the Board in flash mode
* Press and hold the Flash button before connecting the board to USB or programmer connector. Release the flash button after you connect the board.

<h3>PINOUT Description</h3>

<img src="/Photos/Laterna-V2_Pinout.png" width="100%">

<h3>Circuit protection</h3>

<h3>Tested LED Strips:</h3>
WS2812, WS2815
<br>SK6812

<br>Please take note that this Laterna Version can support 5V and 12V LED strip and Power Supplies => Input Voltage = Output Voltage</br>

<h3>License</h3>
Software used in this guide is open source and licensed under the **MIT License**

<h3>FAQ</h3>

* Can I use this board with my own code?
  - yes, you can write your own code and programm this board. Refer to programming steps section

<h3>Acknowledgment</h3>

We would like to thank WLED Developers for their great job, our platform relies strongly on their work
[![Alt text](https://github.com/Aircoookie/WLED/blob/main/images/wled_logo_akemi.png)](https://github.com/Aircoookie/WLED)
