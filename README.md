# Overview
Demonstration of setting up a state machine using event-driven programming to autonomously flying a drone. This was designed to use a flying quadcopter in Udacity's Unity-based simulator. 

The python code is similar to how a drone would be controlled from a ground station computer or an onboard flight computer. Since communication with the drone is done using MAVLink, this code could be used to control a PX4 quadcopter autopilot with very little modification.

## Goal
The required task is to command the drone to fly a 10 meter box at a 3 meter altitude. 

Autonomous control was done using an event-driven state machine. Each callback checks against transition criteria dependent on the current state. If the transition criteria are met, it will transition to the next state and pass along any required commands to the drone.

## Downloading the Simulator
The demo uses the Udacity simulator which can be downloaded [from this repository](https://github.com/udacity/FCND-Simulator-Releases/releases).





