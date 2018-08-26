# NodeMCU
<img src="img/nodemcu_400.jpg" width="120" align="right" />

An open source IoT prototyping platform with ESP8266 WiFi SoC.\
[Official website](http://nodemcu.com/index_en.html) | [GitHub](https://github.com/nodemcu) | [Wikipedia](https://en.wikipedia.org/wiki/NodeMCU)

1. [About NodeMCU](#about-nodemcu)
1. [Setting up Arduino IDE](#setting-up-arduino-ide)
1. Example
1. Example

## About NodeMCU
<img src="img/nodemcu_pinout.png" width="400" />

## Setting up Arduino IDE
Setup Arduino IDE to work with NodeMCU by following the steps.
1. Adding board modules for NodeMCU.
   * From __File__ menu, select __Preferences...__ to open Preferences Dialog.
   * In the field __Additional Boards Manager URLs__ insert the URL:\
     `http://arduino.esp8266.com/stable/package_esp8266com_index.json`
   * From __Tools > Board__ menu, select __Boards Manager...__.
   * In the __Boards Manager__, select __esp8266__ from the list and install.
2. Configuring for the board.
   * From __Tools > Board__ menu, select __NodeMCU 1.0 (ESP-12E Module)__ in the __ESP8266 Modules__ section.
   * From __Tools > CPU Frequency__ menu, select __80 MHz__.
   * From __Tools > Upload Speed__ menu, select __115200__.
   * From __Tools > Port__ menu, select the corrisponding COM port or USB port.

按以下步驟設定 Arduino IDE 加入 NodeMCU 支援。 
1. 增添 NodeMCU 開發版模組
   * 從 __File__ 選單，選擇 __Preferences...__ 開啟 Preferences 對話框。
   * 在 __Additional Boards Manager URLs__ 欄位，加入以下網址：\
     `http://arduino.esp8266.com/stable/package_esp8266com_index.json`
   * 從 __Tools > Board__ 選單，選擇 __Boards Manager...__ 。
   * 在 __Boards Manager__ 的清單中，選擇 __esp8266__ 並安裝.
2. 調整 Arduino 設定
   * 從 __Tools > Board__ 選單，選擇 __NodeMCU 1.0 (ESP-12E Module)__ （在 __ESP8266 Modules__ 類別）。
   * 從 __Tools > CPU Frequency__ 選單，選擇 __80 MHz__.
   * 從 __Tools > Upload Speed__ 選單，選擇 __115200__.
   * 從 __Tools > Port__ 選單，選擇對應的序列埠(COM port)或 USB 埠。

----
More tutorials:
* https://oranwind.org/-esp8266-nodemcu-zai-arduino-ide-she-ding-nodemcu/
* http://web.htjh.tp.edu.tw/B4/106iot/NodeMCU使用介紹.pdf
* http://pizgchen.blogspot.com/2017/04/nodemcu-lab0.html
