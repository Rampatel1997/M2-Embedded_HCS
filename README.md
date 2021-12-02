# M2_Embedded_HCS
## HCS-Heat Control System

### THEORY:>

The heat control system is basically used to control the temperature of a car seat. When a user or driver of the car gets seated on a car, the button sensor gets activated.
After that, the user gets access to turn on the heater. The temperature sensor keeps monitoring the temperature and sends the analog value to the microcontroller.
The microcontroller processes the analog input of the temperature sensor and outputs a temperature value through serial communication.
All the activities of the control system are done on a microcontroller called Atmega328.

### SIMULATION:>

The functionality of the heat control system is coded in embedded c and the working is demonstrated using simuation in a software called SimulIDE.
Below shows two images where in the 1st image shows the status of the simulation when the system is OFF and the second image shows the status of the system when it is ON. 

#### ON

![ON](https://github.com/hemanthasapu/embedded_systems_project_256889/blob/main/simulation/Simulation.gif)

#### OFF

![OFF](https://github.com/hemanthasapu/embedded_systems_project_256889/blob/main/simulation/Simulation_OFF.PNG)

#### Outputs

|Circuit|RAM Table|
|:--:|:--:|
|![CIRCUIT](https://github.com/hemanthasapu/embedded_systems_project_256889/blob/main/simulation/Circuit.gif)|![RAM_TABLE](https://github.com/hemanthasapu/embedded_systems_project_256889/blob/main/simulation/RAM_table.gif)|
|CRO|Serial Monitor|
|![CRO](https://github.com/hemanthasapu/embedded_systems_project_256889/blob/main/simulation/Oscilloscope.gif)|![ON](https://github.com/hemanthasapu/embedded_systems_project_256889/blob/main/simulation/Serial_Monitor.gif)|


[![C/C++ CI](https://github.com/Rampatel1997/M2-Embedded_HCS/actions/workflows/c-cpp.yml/badge.svg)](https://github.com/Rampatel1997/M2-Embedded_HCS/actions/workflows/c-cpp.yml) [![CI](https://github.com/Rampatel1997/M2-Embedded_HCS/actions/workflows/main.yml/badge.svg)](https://github.com/Rampatel1997/M2-Embedded_HCS/actions/workflows/main.yml) [![Compile-Linux](https://github.com/Rampatel1997/M2-Embedded_HCS/actions/workflows/compile.yml/badge.svg)](https://github.com/Rampatel1997/M2-Embedded_HCS/actions/workflows/compile.yml) [![GitInspector](https://github.com/Rampatel1997/M2-Embedded_HCS/actions/workflows/GitInspector.yml/badge.svg)](https://github.com/Rampatel1997/M2-Embedded_HCS/actions/workflows/GitInspector.yml) [![Linux C/C++ CI](https://github.com/Rampatel1997/M2-Embedded_HCS/actions/workflows/Linux-c-cpp.yml/badge.svg)](https://github.com/Rampatel1997/M2-Embedded_HCS/actions/workflows/Linux-c-cpp.yml) [![cppcheck](https://github.com/Rampatel1997/M2-Embedded_HCS/actions/workflows/codequality.yml/badge.svg)](https://github.com/Rampatel1997/M2-Embedded_HCS/actions/workflows/codequality.yml)
![code quality score](https://api.codiga.io/project/30167/score/svg)
![code grade](https://api.codiga.io/project/30167/status/svg)
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/11868fe7d6ff4f348d6be9da922d6e22)](https://www.codacy.com/gh/coderakyadav/M2-Embedded_heatcontrolsystem/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=coderakyadav/M2-Embedded_heatcontrolsystem&amp;utm_campaign=Badge_Grade)


### Functionality 

* When the two switches are closed, the first LED glows indicating the actuation of the system and the heater.
* Next the analog input from the temperature sensor is received and digitized.
* The digitized temperature input is visualized using Pulse Width Modulation.
* The corresponding temperature values based on the digitized temperature input is transmitted by the UART protocol. Here the data is displayed on the serial monitor.

## Significance of heat Control Systems
For a company to stay in business and compete with other competitors both locally and
internationally, a company must place more emphasis on quality and efficiency of their
products. For these reasons more companies are now finding ways to developed and
improve control systems in order to be able to achieve best possible productivity at all
stages.

### Some of the significance of heat control systems in a company are as follows:
* Enhanced product quality
* Waste minimization
* Environmental protection
* Greater throughput for a given installed capacity
* Greater yield
* Deferring of costly plant upgrades, and
* Higher safety margins.





