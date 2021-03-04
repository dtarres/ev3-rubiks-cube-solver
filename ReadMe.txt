CubeThunder made by Daniel Tarrés Amselem

This is an EV3 Rubik's cube solver robot made entirely with Lego pieces.
Because of the color sensor limitations, orange stickers have been removed from the cube so as not to confuse with the red ones. I recommend to do this with your cube if you want it to work :)

For the building instructions, just open the .html file without moving the other folder.
If you want, however, you also have the .lxf file which is the LDD file. To use it, you'll have to install if you don't have it yet LegoDigitalDesigner.

To download the program to the robot, use the ROBOTC programme. You have a 10 day free trial of the programme on robotc.net.
When downloading the program, you may have to adjust something:
	Motors:
		MotorA, codenamed sensor, is the motor that moves the color sensor.
		MotorB, codenamed base, is the motor that moves the base.
		MotorC, codenamed agafa, is the motor at the LEFT of the EV3, watching it frontally.
		MotorD, codenamed cop, is the motor at the RIGHT of the EV3, watchong it frontally.
	Sensors:
		Sensor1, codenamed tocsensor, is the touch sensor next to the motor that moves the color sensor.
		Sensor2, codenamed barreja, is the touch sensor at the RIGHT of the EV3, watching it frontally.
		Sensor3, codenamed apretar, is the touch sensor at the LEFT of the EV·, watching it frontally.
		Sensor4, codenamed color, is the color sensor.


You may have noticed that the robot have two options; it solves the cube may it also offers to the user the possibility to scramble it. To solve the cube, just press the LEFT touch sensor, and for scrambling the cube, the RIGHT touch sensor.

*********************************************
v1.0
It is the first version that works and solves the cube.
It uses the "begginer's solving algorithm" for humans; not a fast algorithm.
For the scrambling, it uses a fast-programmed algorithm that is not efficient. It is just a try and it wil be improved with the next updates.
Scanning the cube take about 90 seconds, and solving the cube, between 7 and 9 minutes.

**********************************************




Copyright © 2014-2015 Daniel Tarrés Amselem

LEGO and MINDSTORMS are trademarks of the LEGO Group
Rubik's Cube is a trademark of Seven Towns Limited

Disclaimer: thoughts and opinions expressed here are my own
