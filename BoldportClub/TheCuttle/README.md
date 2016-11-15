# #266 TheCuttle

A bare-bones Arduino-compatible kit from The Boldport Club (Project #6).

![Build](./assets/TheCuttle_build.jpg?raw=true)


[:arrow_forward: return to the LEAP Catalog](http://leap.tardate.com)

## Notes

The Cuttle is a bare-bones Arduino-compatible soldering kit. It was first designed as commissioned work for [Embecosm](http://www.embecosm.com/), who made it open source hardware.

What's different about this board? It is by far the most beautiful Arduino-like board I own!

### Parts & Unboxing

![kit_packaging](./assets/kit_packaging.jpg?raw=true)

![kit_unboxing](./assets/kit_unboxing.jpg?raw=true)

| Ref      | Item                                                      | Qty |
|----------|-----------------------------------------------------------|-----|
| S1       | Tactile switch, TE Connectivity, FSM4JRT                  |   1 |
| U1       | ATMega328-PU microcontroller, Atmel, ATMEGA328-PU         |   1 |
| C1,2,3,4 | 0.1µF ceramic capacitor, Multicomp, MC0805Y104M500A2.54MM |   4 |
| C5,6     | 22pF ceramic capacitor, Multicomp, MC0805N220J500A2.54MM  |   2 |
| C7       | 10µF electrolytic capacitor, Multicomp, MCMR35V106M4X7    |   1 |
| R1       | 10KΩ resistor, Multicomp, MCF 0.25W 10K                   |   1 |
| D1       | Small signal diode, Multicomp, 1N4148                     |   1 |
| Q1       | 16MHz crystal, TXC, 9B-16.000MAAJ-B                       |   1 |
| -        | DIP socket, TruConnect, DS1009-28 AT1NS                   |   1 |
| -        | 18 contacts header, Multicomp, MC34737                    |   2 |
| -        | 6 contacts right-angle header, Multicomp, MC34751         |   1 |


## Programming the Cuttle

I'm using a cheap [CH340G-based USB to UART adapter](https://www.aliexpress.com/item/CH340-module-USB-to-TTL-CH340G-upgrade-download-a-small-wire-brush-plate-STC-microcontroller-board/32354359382.html).
With the
[correct drivers installed](../../notebook/arduino.md#arduinos-using-the-ch340g-serial-chip),
it shows up in the Arduino IDE and programming works like any other Arduino board.

![TheCuttle_programming](./assets/TheCuttle_programming.jpg?raw=true)

## Construction

![Breadboard](./assets/TheCuttle_bb.jpg?raw=true)

![Schematic](./assets/TheCuttle_schematic.jpg?raw=true)

Finished assembly:

![kit_upper](./assets/kit_upper.jpg?raw=true)

Underside; I haven't cleaned it after soldering:

![kit_lower](./assets/kit_lower.jpg?raw=true)

Nice "Boldport" solder domes! A few flux splatters I haven't cleaned up.
I also made a bit of a mistake with the pins - I pushed them flush from the top but forgot to ensure they were fully aligned.

![kit_lower_points](./assets/kit_lower_points.jpg?raw=true)

## Credits and References
* [TheCuttle](http://www.boldport.club/shop/product/390973459) - in the Boldport shop
* [TheCuttle](http://www.boldport.com/tc/) - project page
* [TheCuttle](https://github.com/boldport/thecuttle) - OSH files on GitHub
* [ATMEGA328P datasheet](http://parts.io/detail/1829384/ATMEGA328P-AU) - parts.io
* [USB to TTL converter UART module CH340G CH340 3.3V 5V switch](https://www.aliexpress.com/item/CH340-module-USB-to-TTL-CH340G-upgrade-download-a-small-wire-brush-plate-STC-microcontroller-board/32354359382.html) - the USB programming adapter I'm using
* [ATmega168/328-Arduino Pin Mapping](https://www.arduino.cc/en/Hacking/PinMapping168)