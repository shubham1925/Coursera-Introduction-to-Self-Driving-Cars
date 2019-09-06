# Coursera-Introduction-to-Self-Driving-Cars
Code for the simulation of a self driving car on Carla Simulator

In this project, the goal was to implement a simple PID controller for the lateral and longitudinal control of a car on a racetrack.
There are 2 important files for configuring the Carla simulator and the controller.

The first one is module7.py
In this file, you can set the map to be used, the weather conditions and the pedestrian density, etc. The comments are self-explanatory.

The second file is the controller2d.py
This file is where you have to implement the PID controller for the lateral anf longitudianl control seperately.
I have however initialized the values of Kp, Ki, and Kd to 0. This way you can tune your own self driving car to achieve the required number of waypoints
