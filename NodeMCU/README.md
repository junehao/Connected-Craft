# NodeMCU

An open source IoT prototyping platform with ESP8266 WiFi SoC.\
[Official website](http://nodemcu.com/index_en.html) | [GitHub](https://github.com/nodemcu) | [Wikipedia](https://en.wikipedia.org/wiki/NodeMCU)

1. [Setting up NodeMCU](#setting-up-nodemcu)
1. Example
1. Example

References:
* https://oranwind.org/-esp8266-nodemcu-zai-arduino-ide-she-ding-nodemcu/
* http://web.htjh.tp.edu.tw/B4/106iot/NodeMCU使用介紹.pdf
* http://pizgchen.blogspot.com/2017/04/nodemcu-lab0.html

## Setting up NodeMCU

1. Downloading and installing Arduino IDE
1. Configuring Arduino IDE
   * Open __Preferences...__ dialog, in __Additional Boards Manager URLs__ insert the following URLs:
     - `http://arduino.esp8266.com/stable/package_esp8266com_index.json`
   * Under __Tools > Board__, select __Boards Manager...__. When the __Boards Manager__ dialog is open, wait until the database is loaded.
   * In the list, select __esp8266__ and click `Install` to install the board data.
   * Under __Tools > Board__, select `NodeMCU 1.0 (ESP-12E Module)`.
   * Under __Tools > Port__, select the corrisponding COM port (or USB port).
