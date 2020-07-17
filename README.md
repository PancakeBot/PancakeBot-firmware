# PancakeBot-firmware
This firmware is a variant of Marlin that allows for control of the pneumatic system for PancakeBot®. 
Useful information
Marlin_main.cpp holds the case instructions for control of the vacuum pump speed based on the "Pressure" knob
on the PancakeBot Console.
The AIR_PUMP is located on pin 9
Cardreader.cpp holds the code for the AIR_PUMP and LED_SDERROR, and LED_WORKING, LED_POWEROFF, LED_POWERON
pins.h define the pin configurations of the board.  
