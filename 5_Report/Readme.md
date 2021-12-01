## Heat Control System

## Introduction

The heat control system is used to control the temperature of the car seat. When a person gets seated on a car, the button sensor will be activated. After that, the user gets access to turn ON the heater. The temperature sensor keeps monitoring the temperature and sends the analog value to the microcontroller. The microcontroller processes the analog input of the temperature sensor and outputs a temperature value through serial communication. All the activities of the control system are done on a Atmega328 microcontroller.

## Components used

ATmega328 microcontroller 

temperature sensor (Potentiometer)

Switches(button and heater)

LED 

LCD display

## Software used

SimulIDE

GCC Compiler for AVR

Code block

## Features

The System will be able to tell whether a person is seated or not.

A person once seated gets the access to turn ON the heater.

The temperature sensor keeps monitoring the temperature and sends the analog value to the microcontroller.

## SWOT - Strengths, Weakness, Opportunities and Threats

### Strengths

Robust in nature 

low cost

Easily accessible by the any person

High efficiency

### Weakness

This system can be used at low to moderate temperature.

### Opportunities

This system can be expanded by adding few more features depending on the user requirement. 

### Threats

This system cannot be used for very high temperature.

## 4W's and 1H

*What* - Heating control system in a vehicle

*Where* - Used in almost all of the passenger vehicles

*When* -  When temperature is low

*Why* - To maintain body temperature

*How* - By using sensors

## Simulation

The functionality of the heat control system is coded in embedded c and the working is demonstrated using simuation in a software called SimulIDE.
Below shows two images where in the 1st image shows the status of the simulation when the system is OFF and the second image shows the status of the system when it is ON. 

### ON
![ON](https://github.com/hemanthasapu/embedded_systems_project_256889/blob/main/simulation/Simulation.gif)

### OFF
![OFF](![Screenshot (335)](https://user-images.githubusercontent.com/94376599/144197395-ac7d91f3-5100-49b0-9b4c-805ca6bde339.png))

### Outputs

|Circuit|RAM Table|
|:--:|:--:|
|![CIRCUIT](https://github.com/hemanthasapu/embedded_systems_project_256889/blob/main/simulation/Circuit.gif)|![RAM_TABLE](https://github.com/hemanthasapu/embedded_systems_project_256889/blob/main/simulation/RAM_table.gif)|
|CRO|Serial Monitor|
|![CRO](https://github.com/hemanthasapu/embedded_systems_project_256889/blob/main/simulation/Oscilloscope.gif)|![ON](https://github.com/hemanthasapu/embedded_systems_project_256889/blob/main/simulation/Serial_Monitor.gif)|

### Functionality 

* When the two switches are closed, the first LED glows indicating the actuation of the system and the heater.
* Next the analog input from the temperature sensor is received and digitized.
* The digitized temperature input is visualized using Pulse Width Modulation.
* The corresponding temperature values based on the digitized temperature input is transmitted by the UART protocol. Here the data is displayed on the serial monitor.







