**Table Of Contents:**
- Concept
- Technologies Used
- Setup
- Getting started
- Prerequisites
- Hardware used
- General instructions

**Concept:**
This project is to obtain signals from brain using EEG Headset and provide to Raspberry Pi via Bluetooth interface for controlling motions of wheelchair using Attention Level and Blinking Strength Parameters.

**Technologies Used:**
Python 2.7
EEG Headset

**Setup:**
motor.py - for controlling the motors
ultrasonic.py - for obstacle detection using ultrasonic sensor
blink.py - for detecting eye-blinks
run.py - all above codes are imported and integrated with attention level of the patient to control motion of the wheelchair

**Getting started:**
These instruction will get you a copy of the project up and running on your local machine for development and testing purpose. 

**Prerequisities:**
Sound knowledge of python programming
Good grip in using Rpi

**Hardware used:**
Raspberry pi 3B+, Neurosky Mindwave mobile 2, ultronosic sensor, gyroscope, motor driver and DC motors   

**General instructions:**
1.  Boot the rpi by installing an OS in it. Preferablly Rasbian
2.  Once booted, open Python IDE
3.  Start writing the code/editing
4.  Once done, save it and open terminal
5.  Set the appropriate directory in the terminal
6.  Wear the Neuropy headset, switch it on, look for a blue light on it, and make sure it is firmly touching your forehead
7.  Run rfcomm
8.  Once done, execute run.py
9.  In case of an error stop the code and rerun it.
