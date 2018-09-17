# arduino-epaper-demo
Demo of e-paper display on [Open Hardware Summit badge](https://hackaday.io/project/112222-2018-open-hardware-summit-badge) using Arduino libraries

## Instructions
==============
* Install the latest Arduino IDE and add the ESP32 board options to the Board Manager:
  * https://dl.espressif.com/dl/package_esp32_index.json
* Make sure the board is set to "ESP32 dev module"
* Make sure the serial port is the serial adapter.
* Wire up GND, RX, TX to the FTDI.
* Connect the IO0 pin to GND.
* Insert Batteries
* The module should power up and go into programming mode (IO0 low on powerup or reset)
* Click program in the Arduino IDE.
* The board should program.
* Un-ground IO0 and remove and reinsert the batteries.
* If this does not work then swap RX and TX and repeat the process
