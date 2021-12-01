# Requirements

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

## Detail Requirements

### High Level Requirements


| **ID** | **Description** |
| :- | :- |
|HLR1|Microcontroller unit    |
|HLR2|Switches|
|HLR3|Temperature sensor|
|HLR4|Heater|
|HLR5|Display CDD CRO|

### Low Level Requirements


| **ID** | **Description** | **HLR ID** |
| :- | :- | :- |
|LLR1|ATMega328|HLR1|
|LLR2|ADCand Potentiometer|HLR3|
|LLR3|Thermo electric module|HLR4|
|LLR4|LCD and LED, PWM|HLR5|




