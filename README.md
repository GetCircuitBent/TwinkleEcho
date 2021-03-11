# Twinkle Echo
## Simple Echo/Filter Effect Module

This module is intended to be very simple and small so it can be worked into keyboards/etc as a mod. 

## Notes:
* Voltage is very picky, requires 4.5-6 volts but seems to work best sticking right at 5 volts
* To only use Echo effect, simply do not connect the secondary filter resistor, capicitor, and control pot (marked on schematic)
* Distorts easily based on input signal. Keep input low for clean echo, or use input level control as a gain/distortion
* Resistor to Filter Control (R5) adjusts sweep value. Default is set for very large cutoff for dealing with high input, heavily distorted signals. Increase the value of this resistor to reduce the sweep for better control in low signal/clean applications.
* Resistor to Echo Control (R1) can be 1k if it saves you buying another resistor value, but I think 2k is a bit nicer if you have them already.

## Parts List
(Asterisked parts only needed if you want to build out the filter)
* PT2399 IC
* 50k Linear Potentiometer
* *1k Linear Potentiometer
* 0.1uF film (or ceramic) capacitors x *6 (5)
* 10uF electrolytic capacitors (any voltage rating 16v or higher) x 3
* Resistors:
  * 10k x2
  * 1k x1
  * 2k x1 (can use a second 1k if it saves you an order)
  * *100R x1 (alter this value to change the filter range)

## Demo:
https://youtu.be/kHf7WUVE1LU

#### Not required or expected by any means, but if you like it you can use the Sponsor button to buy me a beer!
