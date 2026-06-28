# Smart Garage System - [ C++ & Arduino ]

## About Project:
"System that detects the distance of the oncoming car and decides to rotate the STOP sign automatically and activate the alarm."

## How the system works:
* The **trigger pin** generates wave that go until it reaches the body.
* The **echo pin** measures the time that the wave will go.
* Calculate Distance : [ (time*speed of sound) / 2 ]
* The **LCD display** will print the distance.
* The **Servo Motor** will rotate the sign "STOP".
* The **Buzzer** "Alarm" will be activated.

## Features:
* Real-time distance tracking.
* Sign "STOP" automatically controlled.
* Printed distance on display.
* Audible Alarm.

## Hardware Components:
* Arduino Uno
* HC-SR04 Ultrasonic Sensor
* SG90 Servo Motor
* 16x2 LCD Display (with I2C)
* Buzzer
* Breadboard & Jumper wires