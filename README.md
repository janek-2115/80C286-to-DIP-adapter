This is a simple two-layer PCB design that converts the 80286 CPU in the PLCC68 package to DIP62 package.
First you need to get the PLCC68 socket, then sodler it on the board making sure that the notch on the socket matches the notch/circle on the PCB.
There are only 62 pins going out of the board, since there are 6 NCs on the CPU itself.
The PCB is made so that all of the addresing and data pins are next to eachother. 
There are 2 VCC pins and 3 GND pins, all of them need to be connected to +5V/GND.
The pins that are active-high are labeled using normal text, while active-low pins are in negative text.
