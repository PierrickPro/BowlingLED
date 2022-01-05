# Bowling LED Strips using Arduino

[Project Video Demo](https://youtu.be/nXO_UD2gey4)

5 bored Concordia Gina Cody students decided to play bowling in their hallway while being stuck at home in March 2020.<br/>
2 LED strips, one on each side of the bowling alley were connected to an Arduino.

The code has 2 modes:
- animations mode
- bowling mode

The animations were taken from the FastLED library examples, DemoReel100.ino.

A push button is used to switch between both modes.

The bowling mode uses HC-SR04 ultrasonic sensors to check if pins are standing.<br/>
We only had space for 6 pins, se we used 3 ultrasonic sensors, one in front of each row of pins.<br/>
If no pins are detected, the LEDs change animation, with green strobe. 

We used empty water bottles as pins, and a small basketball to play.<br/>
Cases were 3D printed for the Arduino and sensors to mount them on the wall.<br/>
STL files can easily be found online.

Possible improvement: implement Protothreads
