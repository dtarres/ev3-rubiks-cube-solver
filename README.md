# ev3-rubiks-cube-solver

CubeThunder made by Daniel Tarrés Amselem

This is the final high-school project that I did back in 2014 with a colleague, at the age of 17, before any of us started out computer science college degree or attended any programming course.

It is a Rubik's cube solver made with a Lego EV3 robot set, and some Lego Technic pieces. Due to color sensor limitations, orange stickers were been removed from the cube so as not to confuse with the red ones.

The algorithm applied is the beginner's method, as the main objective of this project was to make a fully functional robot that solved the cube, without considering speed nor efficiency.

A digitalized version of the robot is provided. There's a html file with step-by-step instructions, and the lxf file in order to make any modification using LegoDigitalDesigner.

In order to program the robot, a software called ROBOTC was used, which provides a compiler and an IDE for some Lego robots.

A demonstration of the process is provided using the [following link](https://www.youtube.com/watch?v=P05Q6jSf34c).

The following configuration was applied:
####Motors:
 - MotorA, codenamed sensor, is the motor that moves the color sensor.
 - MotorB, codenamed base, is the motor that moves the base.
 - MotorC, codenamed agafa, is the motor at the LEFT of the EV3, watching it frontally. It is the one that holds the cube.
 - MotorD, codenamed cop, is the motor at the RIGHT of the EV3, watching it frontally. It is the one that pushes the cube.
####Sensors:
 - Sensor1, codenamed tocsensor, is the touch sensor next to the motor that moves the color sensor.
 - Sensor2, codenamed barreja, is the touch sensor at the RIGHT of the EV3, watching it frontally.
 - Sensor3, codenamed apretar, is the touch sensor at the LEFT of the EV3, watching it frontally.
 - Sensor4, codenamed color, is the color sensor.


Depending on what mode it starts, the robot can solve the cube or scramble it in a simple way.

Scanning the cube take about 90 seconds, and solving the cube, between 7 and 9 minutes.
It is not necessary to put the cube with a specific orientation or scramble situation. The robot detects the orientation of the cube and re-orientate it.
It is also not necessary to have the sensor at any specific position when trying to solve the cube, as the first thing that the robot does is calibrate the position of the sensor.


