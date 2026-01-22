## Project Overview:

The goal of the Laser Tracking Rail System is to use a camera to follow a red laser which produces a pan and tilt motion. This project has the use of software and hardware. It uses a camera which tracks the movement of a red laser in Python using proportional feedback control and Arduino to map servo and step motor positions into pan and tilt motions proportional to the laser position. This project directly connects to Navigation and control systems.

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



## System Diagram + Control Math
![IMG_7990](https://github.com/user-attachments/assets/7defe666-5eae-448b-986d-d7c53ec99bf1)
<img width="287" height="141" alt="image" src="https://github.com/user-attachments/assets/30ecec48-8681-4990-8616-8878287bf713" />


## Prototype

![IMG_7840](https://github.com/user-attachments/assets/c6cb69c4-9904-4714-9796-178bc69b348e)
![IMG_7998](https://github.com/user-attachments/assets/4374c666-4e2f-4590-9a2e-a9bbc566ce0a)

## Arduino and Motor Control Board and Diagram
![IMG_7991](https://github.com/user-attachments/assets/5cbe9089-db1b-4d3b-878e-a94ac1591af7)
![IMG_8005](https://github.com/user-attachments/assets/0b17aecd-b6a5-459f-a251-85105f97cb33)
![IMG_8002](https://github.com/user-attachments/assets/aaf20f24-cfd1-4960-8792-a8b55186e2d6)


