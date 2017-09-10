# OPi-Fan

Installation:
- Unpack the archive
- Define the value set that you need.
    Pina, minimum and maximum temperature, the number of Hall sensor pulses per revolution of the cooler, while the demon of the reaction, the minimum duty cycle.
- compile
g++ OPi-fan.c  -o OPi-fan  -lpthread -lwiringPi
- Copy of your directory in /usr/local/bin
cp ./OPi-fan /usr/local/bin
