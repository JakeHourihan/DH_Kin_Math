# DH_Kin_Math
Robotic Linkage Kinematics Calculator Based on DH Tables

The plan for this software is to use modified DH frame assignments in order to calculate kinemtic data for a robotic manipulator such that a microcontroller and a microcomputer can communicate over serial to perform actions on a robot with a high relative speed for a hobby grade project. Standard microcontrollers typically do not have flash memory large enough to comfortable store both the advanced level math as well as the digital control software used to communicate with the electro-mechanical and electrical components onboard the hardware. By breaking this up, between devices, the microcontroller has a relatively low computational load, allowing for faster real-world response times.

Later-stage plans for this include a user-friendly GUI for interaction with a small form-factor 3D-printable robot manipulator that is being designed in parallel.