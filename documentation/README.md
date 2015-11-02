# eeZee MicroSD User Guide

eeZee MicroSD makes it convenient and quick to add a microSD card to your Breadboard Arduino, no jumper wires required. Just insert it into the breadboard next to your Arduino ATmega328P and you're ready to go!

Want one? [Buy now on Tindie](https://www.tindie.com/products/edit/eezee-microsd-breakout-4/).

## Quick Start

 * Install D10-D13 pin headers (see *How to Assemble* below)
 * Install VIN and GND pin headers
 * Place next to breadboard Arduino matching D10-D13 pins
 * Connect power to VIN, GND to ground
 * Open the Arduino IDE.
 * Select ```ReadWrite``` from the ```File```>```Examples```>```SD``` submenu.
 * Assemble and upload to your Arduino

## How to Assemble

Assembly is easy. And, you can learn how to solder at the same time. Review [Sparkfun's Soldering Tutorial](https://learn.sparkfun.com/tutorials/how-to-solder---through-hole-soldering) if you need to. Here's a helpful info-graphic from the tutorial:

![soldering infographic](https://cdn.sparkfun.com/assets/c/d/a/a/9/523b1189757b7fb36e8b456b.jpg)

### You'll need
 * Soldering iron, 40W
 * Sponge to clean the iron (I recommend a brass sponge)
 * Workbench with plenty of light
 * Ventilation since breathing flux fumes is irritating
 * Soldering surface (e.g., marble tile sample)
 * Rosin core solder 0.022” or 0.032” diameter
 * Kester #2331-ZX flux pen (optional)

### Pin Headers

Install the adjacent 4-pin D10-D13, 2-pin VIN/GND headers in your breadboard.

Place the eeZee MicroSD on top of the pin headers, socket side up.

Solder D13 and VIN, holding the board level.

Then, solder the remaining pins.

### Power Rail Pins (Optional)
Installing power rail pins allows you to power the board without needing jumpers.

Install a 2-pin header on the power rail of your breadboard.

Place the eeZee MicroSD into the board so these two new pins engage one of the VCC/GND large holes.

Solder the pins in place.

## Insert/Remove the MicroSD Card

Open the flip lid version by first unlocking the lid by pushing forward toward the pin headers. Then, flip the lid up and remove the microSD card. To insert a card, place it in the socket with the lid up. Then close the lid, and pull it back away from the pin headers to lock it.

To install or remove the card from a push/pull socket, push the microSD in until it stops, then release. This will either lock or unlock it. The action is similar to using a retractable ball point pen. Once unlocked, you can remove the card.

## Power Options
You can power your board with 3.3V or with 5V. There's a solder jumper on the bottom of the board that you'll solder depending on the supply voltage.

For a 5V supply, solder the REG side of the jumper. For a 3.3V supply, solder the BYP side of the jumper.

You can supply voltage from using the breadboard power rails (see *Power Rail Pins* above) or by using jumpers to the VIN/GND pins.

## Code Examples and Documentation
* [Arduino SD library reference](https://www.arduino.cc/en/Reference/SD)
* [My Example Code](https://github.com/shimniok/eeZeeMicroSD/tree/master/examples)
* Also, example sketches are available in the Arduino IDE. Select an example from the ```File```>```Examples```>```SD``` submenu.
