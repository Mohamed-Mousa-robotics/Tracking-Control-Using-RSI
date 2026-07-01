# Tracking-Control-Using-RSI
Development of ANFIS Controller for Trajectory Tracking Control Using ROBO2L MATLAB Toolbox for KUKA Industrial Robot via RSI
# Overview
The goal of this work is to develope high level controller for trajectory tracking control of real KUKA KR6 R900 SIXX by controlling its velocity using ROBO2L MATLAB Toolbox with Robot Sensor Interface (RSI).In this work, the Fuzzy Logic Controller (FLC), and adaptive neuro-fuzzy inference system (ANFIS) were developed based on point-to-point (PTP) motion and compared with linear controller.
# Background
The RSI is a supplementary software component made by KUKA to transmitt the data between extrnal sensors of the system that were substituted and emulated by MATLAB and the robot's controller.
the ROBO2L toolbox uses the UDPtoRSI.dll Structure that was built using C language to enable the communication between robot and computer. it was established to connect with robot, reading and writiing the position of the robot and sending commands for the robot. the following figure illustrates the structure of ROBO2L MATLAB toolbox. 
