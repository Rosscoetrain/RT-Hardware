# RT Solenoid Turnout Driver

This is deprecated;

It has been combined into either of these:

https://github.com/Rosscoetrain/RT-Hardware/tree/master/RT_Pulse_8_decoder

https://github.com/Rosscoetrain/RT-Hardware/tree/master/RT_Pulse_8_HP_decoder


It is here for reference for users.




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

1 - 6 pin (3x2) male header

4 - 3 way 2.54mm (0.1”) pitch screw terminal



#### Maximum use:

This is 8 turnouts and CDU

2 - ULN2803 Darlington driver

1 - TIP41C NPN power transistor

1 - 1N4001 diode

2 - 4700uF 35V electrolytic capacitor

1 - 6 pin (3x2) male header

8 - 3 way 2.54mm (0.1”) pitch screw terminal

1 - 2 way 5.08mm (0.1”) pitch screw terminal


