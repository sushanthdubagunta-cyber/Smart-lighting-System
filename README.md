# Smart Lighting System Using LDR and Arduino UNO

## Project Overview

This project demonstrates a Smart Lighting System developed using an Arduino UNO and an LDR (Light Dependent Resistor) in Tinkercad. The system automatically controls an LED based on the surrounding light intensity. When the ambient light level decreases, the LED turns ON automatically, and when sufficient light is available, the LED turns OFF.

## Objective

The objective of this project is to understand sensor interfacing with a microcontroller and implement a simple automation system using light intensity sensing.

## Components Used

* Arduino UNO
* LDR (Light Dependent Resistor)
* LED
* 220Ω Resistor
* Connecting Wires
* Tinkercad Simulator

## Working Principle

The LDR continuously senses the surrounding light intensity and sends an analog signal to the Arduino through pin A0. The Arduino compares the sensor value with a predefined threshold value. If the light intensity falls below the threshold, the Arduino switches ON the LED. Otherwise, the LED remains OFF.

## Features

* Real-time light intensity monitoring
* Automatic LED control
* Threshold-based decision making
* Energy-efficient lighting automation
* Easy implementation using Tinkercad

## Circuit Connections

* LDR connected to Analog Pin A0
* LED connected to Digital Pin 13 through a 220Ω resistor
* Connections made using Tinkercad connecting wires

## Applications

* Automatic Street Lighting
* Smart Home Lighting
* Garden Lighting Systems
* Energy Conservation Projects
* Building Automation Systems

## Software Used

* Tinkercad Circuits
* Arduino Programming Language (Embedded C/C++)

## Result

The Smart Lighting System was successfully simulated in Tinkercad. The Arduino continuously monitored ambient light conditions and automatically controlled the LED based on the detected light intensity, demonstrating a simple yet effective automation system.


