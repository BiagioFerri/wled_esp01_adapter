
# ESP01 WLED ADAPTER
The most compact board for the ESP-01 format to control LEDs using the WLED firmware.

<img src="https://github.com/BiagioFerri/wled_esp01_adapter/blob/main/images/boardSide.jpg" width="300" height="300"> <img src="https://github.com/BiagioFerri/wled_esp01_adapter/blob/main/images/esp01side.jpg" width="300" height="300">

## ⚙️ Features
* 5V or 12V power supply
* Up to 2A of power
* Fuse for absorption protection (ex. laptop USB)
* Type C connector
* Configuration to be programmed directly (need appropriate cable)

## 💻 How to program
* Using the appropriate cable plug&play (coming soon), push flash button and follow [wled guide](https://kno.wled.ge/basics/install-binary/)
* Create your own usb C cable follow the schema connecting RX & TX (make sure R0 are soldered) to uart adapter (ex ft232)

## 📱 How to use
* Solder your LED strip respecting the pin out indicated on the board (Only addressable LEDs with a single data pin are compatible, see [wled documentation](https://kno.wled.ge/basics/compatible-led-strips/))
* Solder your protection fuse (OPTIONAL)
* Connect a usb C cable to the board with a 5V or 12V power supply
* Configure your led number and max current absorption connecting to the board (see [wled documentation](https://kno.wled.ge/basics/top5_mistakes/))
* Make sure GPIO2 as control PIN
* Play and create your light project

## 🔨 How to build
* Produce your pcb using the different services available (ex jlcpcb)
* Solder the components following the diagram
* PCB files & BOM available soon 

## 💸 How to buy
* Wled controller with ESP-01 integrated with latest firmware version flashed and configured, you just have to connect it to the power supply and solder your led strip [AVAILABLE on Ebay]()
* Wled controller configured + soldered led strip (COMING SOON)
* Plug&play programming cable (COMING SOON)

## 🙏 Thanks to
* [All wled contributors](https://github.com/wled/WLED)
