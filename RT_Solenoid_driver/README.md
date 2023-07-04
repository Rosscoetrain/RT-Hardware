# DCC-Solenoid-Turnout-Driver

This board is designed to control dual solenoid turnouts such as the Marklin M track 5117, 5202, 5120, 5214,
5207 or 5128. With or without a capacitor discharge unit (CDU).

The board has a number of options for construction. Below are bill of materials for minimum use and a
completely populated board.

I use a 24V 1A DC power supply with the board and this will power the Marklin turnouts without a CDU.
Other brands of turnouts have not been tested.

The maximum current for any one solenoid is 500mA, this is limited by the ULN2803 darlington drivers.

Full construction and use in the file details.pdf



## Bill of Materials

#### All builds:

1 - PCB
[Buy from pcbway](https://pcbway.com/project/shareproject/DCC_EX_Solenoid_Turnout_Driver_with_Capacitor_Discharge_Unit_8274534c.html)

1 - MCP23017 I2C Serial Interface - 16 bit I/O Expander Module
https://ebay.com.au/itm/265734933121

#### Minimum use:

This is 4 turnouts and no CDU

1 - ULN2803 Darlington driver

3 - 10K 1/8w resistors

1 - 6 pin (3x2) male header

1 - 10 pin female header

1 - 20 pin (10x2) female header

1 - 2 way 2.54mm (0.1”) pitch screw terminal

4 - 3 way 2.54mm (0.1”) pitch screw terminal

1 - 4 way 2.54mm (0.1”) pitch screw terminal


#### Maximum use:

This is 8 turnouts and CDU

2 - ULN2803 Darlington driver

2 - 3mm led (colour of your choice)

1 - TIP41C NPN power transistor

1 - 24V zener diode (optional)

1 - 1N4001 diode

1 - 220Ω 1/8w resistor

1 - 2W10 Bridge Rectifier 2A

1 - 1K 1/8w resistor

3 - 2K2 1/2w resistors

3 - 10K 1/8w resistors

2 - 4700uF 35V electrolytic capacitor

1 - 6 pin (3x2) male header

1 - 10 pin female header

1 - 20 pin (10x2) female header

8 - 3 way 2.54mm (0.1”) pitch screw terminal

1 - 4 way 2.54mm (0.1”) pitch screw terminal

1 - 2 way 5.08mm (0.1”) pitch screw terminal


