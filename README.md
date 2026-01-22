## Project Overview:

The goal of the Laser Tracking Rail System is to use a camera to follow a red laser which produces a pan and tilt motion. This project has the use of software and hardware. It uses a camera which tracks the movement of a red laser in Python and uses Arduino to turn these motions into pan and tilt motions using a servo and step motor. This project directly connects to Navigation and control systems.

## System Architecture:
-Hardware: Arduino UNO R4 Wifi, SG90 Servo, NEMA 17 55Ncm STEP MOTOR, 500mm T8 KFL08 Trapezoidal Lead Screw, 500mm, MGN12H Linear Rail Guide, TMC2209, LC Circuit protection

-Software: Python, Arduino, OpenCV, PySerial 

## Key Concepts:
-Proportional Feedback Control
-Serial Communication
-Mechanical structure

## Results:
-Motor and Servo respond correctly to laser position
-Servo makes some sharp overcorrections causing oscillation (resolved with Lower correction Gain)
-Step motor moves very slowly 
-Loud noises of step motor when moving (suggests some misalignment on rail)

## What I'd Improve:
- Replace Step Motor with an Electric motor and H-Bridge Control board. (Offers Higher speed)
- Make the Linear Rail Guide longer than lead screw
  



