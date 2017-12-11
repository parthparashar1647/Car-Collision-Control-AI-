# Car-Collision-Control-AI-
Creating a bot that can detect obstacle using ultrasonic sensors and reduce speed or stop to prevent collision with obstacle


(a) Component # 1:
Arduino UNO(ATM328P):
Input: duration of time taken by ultrasonic sound from ultrasonic sensor to the
obstacle and returning to sensor.
Output: right motor speed and left motor speed

Arduino is an open source electronic platform used to read input form ultrasonic
sensor, process the input and according to it apply fuzzy logic give output to
motor controller.


(b) Component # 2:
Ultrasonic Sensor:
Input: Echo Pin
Output: Trig Pin
An Ultrasonic Sensor is a device that can measure the distance to an object by using
sound waves. It measures distance by sending out a sound wave at a specific frequency
and listening for that sound wave to sound wave.


(c) Component #3:
Motor Controller:
Model No.: L298N DC Motor Controller
Output: voltage
Input: Motor Speed of DC motors
A Motor Controller is a device that acts as intermediary between your robot’s
microcontroller, batteries and motors. It is used to regulate the speed of DC motors by
changing the power.


(d) Component #4:
Bluetooth Module:
This is being used to connect the bot with an android app named “Car Bluetooth
RC” through Bluetooth. After connecting the bot with this app, we can control the
movements of bot, i.e., moving forward, backward, left, right.


(e) Component #5:
DC Motor
Input: voltage
Output: Torque
To traverse the bot
