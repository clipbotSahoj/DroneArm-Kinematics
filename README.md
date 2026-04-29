# DroneArm Inverse Kinematics
This project implements a 3-DOF (Degrees of Freedom) Inverse Kinematics solver for a drone-mounted robotic arm. 

## Features
* **Custom IK Solver:** Uses Law of Cosines to calculate joint angles for specific XYZ coordinates.
* **Digital Twin Simulation:** Integrated with RoboDK to validate movements before hardware deployment.
* **Language:** Python 3.13

## How to Run
1. Open RoboDK and name your robot `DroneArm`.
2. Run `pip install robodk`.
3. Run `main.py`.
