# Project Brainstorming

Once you are finished brainstorming your project ideas, fill in each of the sections below. You can continually update this project up to the morning of March 10th (the deadline).

**NOTE:** you should delete the initial sentences provided for each section (only include your own writing).

## Purpose

The purpose of this project is to develop a healthcare app that helps patients monitor their own health and perform simple medical tasks more safely. The system combines real-time sensing and guidance to give users feedback about their body and surroundings.

## Subsystems

### Subsystem 1

Vein Injection Guidance responsible for detecting vein locations for injections. It combines micro servo motors, light/laser guidance, and visual feedback to ensure accurate needle placement, reducing patient discomfort and error.

#### Devices

List, or put in a table, the devices your subsystem will use. 

For each device, include the Component name, Interface type, and link to any documentation you can find about that device.

Micro Servo Motors
Laser Pointer Module

### Subsystem 2

Patient Vital Monitoring monitors patient stress levels and heart rate using skin sensing and biometric sensors. The system collects and processes data in real time, providing alerts for abnormal readings. It integrates into the app to display patient vitals alongside procedural guidance.

#### Devices

GRS Skin Sensing Sensor I2C / Analog
Heart Rate Monitor I2C / Analog

### Subsystem 3

Environment Monitoring checks the patient environment for safety by monitoring temperature and oxygen levels. This subsystem complements the other two by providing context-aware data to enhance patient safety.

#### Devices

Temperature Sensor I2C / Digital
Oxygen Level Sensor Analog / Digital
