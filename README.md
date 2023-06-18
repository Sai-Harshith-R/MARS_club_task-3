# MARS_club_task-3

LINKS OF CODES AND SCREENSHOTS: 

https://github.com/Sai-Harshith-R/MARS_club_task-3/blob/b2ef0e94459327e994d1a0199ad6299a0f70b120/arduino_mars_task_3.ino

https://github.com/Sai-Harshith-R/MARS_club_task-3/blob/c08c3c5a3e4461a5b8e7c8d76831c14609311885/mars_club_task3__2nd_.ino

https://github.com/Sai-Harshith-R/MARS_club_task-3/blob/ff13a6768ffc2aa82a2e1e084d1fa1e8240525d1/screenshot%20mars%20club%20task%203%20(2nd).png

https://github.com/Sai-Harshith-R/MARS_club_task-3/blob/d2e2c32d4d85ed26cb9c6edee9cb619f786f98d4/screenshot%20mars%20club%20task%203.png

INTRODUCTION:

This task uses an MPU-6050 sensor consisting of accelerometer and gyro sensor.
We have to print the values of acceleration and rotation w.r.t X,Y & Z axes measured by MPU6050
As we press the push button, the measurements from sensor should be printed and it should stop printing if we press the push button again.

PROCEDURE:

Take all the apparatus [ARDUINO UNO, jump wires, breadboard, MPU-6050 sensor].
Make sure that VCC and GND of the sensor is connected to 5v and ground of ARDUINO respectively .
Connect the serial clock pin and serial data pin of the sensor to the ARDUINO.
Include "Wire.h" header file for writing the program
Use interrupt statement/function to start and stop the display when push button is pressed
