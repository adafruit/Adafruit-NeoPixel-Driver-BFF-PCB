## Adafruit NeoPixel Driver BFF PCB

<a href="http://www.adafruit.com/products/5645"><img src="assets/5645-04.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit NeoPixel Driver BFF. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5645

### Description

Our QT Py boards are a great way to make very small microcontroller projects that pack a ton of power - and now we have a way for you to quickly add a strand of NeoPixels with a 5V level shifter and a detachable JST PH connector. It's an excellent way to make tiny wearable, cosplay or IoT projects with dazzling LEDs.

We call this the Adafruit NeoPixel Driver BFF - a "Best Friend Forever". When you were a kid you may have learned about the "buddy" system, well this product is kinda like that! A board that will watch your QT Py's back and give it the power and support to drive NeoPixel strips, rings, and panels.

This PCB is designed to fit onto the back of any QT Py or Xiao board, it can be soldered into place or use pin and socket headers to make it removable. Onboard is a 74AHCT125 single-gate level shifter that will take pin A3's output, and shift it up to 5V using the USB power as a reference. The USB power, ground and shifted data is then piped out to a JST PH 2mm 3-pin connector.

If using one of our NeoPixel strips with a JST-PH connector on them already, you can just plug it right in for instant lights. If you're using a common JST SH (black in-line) connector on the strips, you can use a JST-PH-to-female-header cable and use that to plug into the pins on the input of the SH port and/or can jam the wires into the header sockets. 

Note that we connect the USB 5V power directly out to the NeoPixel power pin on the JST PH connector and PH connectors are only rated for about 2 Amps, so it's not for powering directly more than maybe 30-60 NeoPixels (less if they're on full white brightness). 

We include some header that you can solder to your QT Py. You can also pick up an Itsy Bitsy short female header kit to make it removable but compact, you'll just need to trim down the headers to 7 pins long.

Comes as an assembled and tested PCB
For any QT Py or Xiao boards
Uses the 5V input via USB Type-C connector on QT Py to Power 30ish NeoPixels
Level-shifted data from pin A3 default, can solder-jumper select SCL, TX, RX, SCK or MOSI
For driving any WS2812/WS2811/NeoPixel LEDs
NeoPixels and QT Py are not included.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
