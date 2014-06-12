RaspberryPi_LEDs
================

Small Python script to test output of a RPi.

A small snippet of code I made to test the RPi as a part of the Arduino project.

Just sends power through the GPIO ports on the RPi, corresponding to what the user input is, which then lights up a few LEDs connected on a breadboard - nothing fancy.
I was sad to find that there seemed to be a noticeable delay between loop cycles when #4 was run, which gave a jerky feel to the LED sequence. :(
