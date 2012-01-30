MAX31855 Breakout Board
=======================

This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/">Creative Commons Attribution-ShareAlike 3.0 Unported License</a>.

<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-sa/3.0/88x31.png" /></a>
	
Designed By:

*	Ryan McLaughlin <ryan@ryanjmclaughlin.com>


Summary
-------

This is a simple low-cost breakout for the MAX31855 thermocouple to digital interface from Maxim.  Rather than using a standard SOIC to DIP adapter, you can use this handy breakout to connect a thermocouple and the recommended cap for the IC is already included.  Comes with SMT soldering complete and headers loose.  Also included is a 4050 level shifter for using the chip with 5V systems.

**CAUTION: The MAX31855 is for 3.3V only! If connecting to a 5V system, you must use a level shifter!!**

Tutorial
--------

It is simple to get everything up and running.

1.	Install a header or solder jumper wires to the pin connections
2.	Connect a K-Type [Thermocouple](http://en.wikipedia.org/wiki/Thermocouple Thermocouple) to the terminals
3.	Wire the necessary connections to an Arduino or other micro controller, the bare minimum connections are +V, GND, SCK, SO, CS  **CAUTION: The MAX31855 is for 3.3V only! If connecting to a 5V system, you must use a level shifter!!**
4.	If using an Arduino, load one of the samples from the MAX31855 Arduino Library and you should see temperature information in the serial console. With other micro controllers you can access the chip using a standard SPI interface. See MAX31855 data sheet for more details.


Board Specs
-----------

*	Dimensions: 0.6" x 0.6"
*	Chip: MAX31855
*	Voltage: 3.3V
*	Header: 1x3 (2) 0.1" Pitch


Versions
--------

###Version 1.0

Initial version of the board with a small SMT header. <small>Licensed under OSHW</small>

* 	Initial release under Eagle 6.1 on Github
*	DIP format for easy breadboarding
*	Recommended cap is included on the breakout
*	Production dates: 05-2011

####Board Specs
*	Dimensions: 0.6" x 0.6"
*	Chip: MAX31855
*	Header: 1x3 (2) 0.1" Pitch


Purchase
--------

[store.ryanjmclaughlin.com](http://store.ryanjmclaughlin.com). 

