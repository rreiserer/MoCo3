# MoCo3
Under Development

This code is intended to run a multi-microcontroller motor driver system

Edit from second sync attempt
The system uses three motors, each with a Atmega8 being used as a programmable ASIC to control a stepper motor driver and a magnetic encoder. A 32U4 is used as a coordination controller as well as a communication manager for motor commands that are streamed in from an ESP8266-07S WiFi module. Having 5 microcontrollers on board, this project is a tad bit complicated.
