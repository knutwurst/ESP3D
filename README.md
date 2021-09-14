<span align="left"><img src="https://github.com/luc-github/ESP3D/blob/2.1/images/ESP3D.png" width="200px"/></span><span align="left">Firmware for ESP8266/ESP8285  and ESP32 used with 3D printer</span>

[Latest stable release ![Release Version](https://img.shields.io/github/release/luc-github/ESP3D.svg?style=plastic) ![Release Date](https://img.shields.io/github/release-date/luc-github/ESP3D.svg?style=plastic)](https://github.com/luc-github/ESP3D/releases/latest/) [![github-ci](https://github.com/luc-github/ESP3D/workflows/build-ci-2.0/badge.svg)](https://github.com/luc-github/ESP3D/actions/workflows/build-ci-2.0.yml) [![Release Version](https://img.shields.io/github/v/release/luc-github/ESP3D-WEBUI?color=green&include_prereleases&label=WebUI&style=plastic)](https://github.com/luc-github/ESP3D-WEBUI/tree/2.1)      
please use Arduino ide 1.8.9+ with [![Release Version](https://img.shields.io/badge/ESP32-1.0.4-green?style=plastic)](https://github.com/espressif/arduino-esp32/releases/tag/1.0.4) or [![Release Version](https://img.shields.io/badge/ESP8266-2.5.2-green?style=plastic)](https://github.com/esp8266/Arduino/releases/tag/2.5.2)

[Latest development version ![Development Version](https://img.shields.io/badge/Devt-v3.0-yellow?style=plastic) ![GitHub last commit (branch)](https://img.shields.io/github/last-commit/luc-github/ESP3D/3.0?style=plastic)](https://github.com/luc-github/ESP3D/tree/3.0) [![github-ci](https://github.com/luc-github/ESP3D/workflows/build-ci/badge.svg)](https://github.com/luc-github/ESP3D/actions/workflows/build-ci.yml) [![Development  Version](https://img.shields.io/badge/Devt-v3.0-yellow?style=plastic&label=WebUI)](https://github.com/luc-github/ESP3D-WEBUI/tree/3.0)   
please use Arduino ide 1.8.9+ with [![Release Version](https://img.shields.io/badge/ESP32-git-yellow?style=plastic&logo=github)](https://github.com/espressif/arduino-esp32) or [![Release Version](https://img.shields.io/badge/ESP8266-git-yellow?style=plastic&logo=github)](https://github.com/esp8266/Arduino/)

[All releases](https://github.com/luc-github/ESP3D/releases)

This firmware allows not only to have a cheap bridge between Wifi and serial, but also to have a web UI to configure wifi, to monitor 3D printer and even control it, and to make things easy,
UI is fully customizable without reflashing FW.

Firmware should work with any 3D printer firmware (repetier/marlin/smoothieware using GCODE) if serial connection has a correct setup.
I currently use it with my personnal flavor of [repetier for Due based boards](https://github.com/luc-github/Repetier-Firmware-0.92).

The web interface files are present in data directory but UI has it's own repository [ESP3D-WEBUI](https://github.com/luc-github/ESP3D-WEBUI).
* Be aware  ESP3D-WEBUI is for firmware 0.9.99 minimum - previous released version use tpl files which are no more used.
* Note for ESP8266 1MB flash : FW is now too big will all features you need to chose strip the FW and select only some features, also WebUI is now also too big for full multilanguage support to fit the 128K SPIFFS so please use pack with limited language (en +another) https://github.com/luc-github/ESP3D-WEBUI/tree/2.1/languages


### If you like what I do you can buy me a coffee*: [![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://paypal.me/oliverkoester)
<sub>*It doesn't have to be a generous donation. A few cents are enough to show me who is interested in further development. So the motivation stays and I just know that I am not programming for the bin ;)<sub>
