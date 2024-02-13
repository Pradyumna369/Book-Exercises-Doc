# Constrained Device Application (Connected Devices)

## Lab Module 04

### Description

What does your implementation do? 
Integrated Sense Hat emulator into CDA. Implemented code to read humidity, pressure and temperature sensor data from sense hat emulator and also activating HVAC, Humidifier actuators on the emulator.
Sense HAT's LED display is activated to show actuator command

How does your implementation work?
The enableEmulator flag in configuration file(PiotConfig) is set to True to use Sense HAT emulator which is imported from pisense library. Made code changes to SensorAdapaterManager and ActuatorAdapterManager such that if the flag is set to True, the sensor value are read from the emulator and actuator commands are displayed on LED display.


### Code Repository and Branch

URL: https://github.com/Pradyumna36/PIOT-Python-Components.git

### UML Design Diagram(s)

https://github.com/Pradyumna36/Book-Exercises-Doc/blob/labmodule04/labmodule04/CDA-%20Integrated%20sensing%20and%20actuation%20app.png


### Unit Tests Executed

HumidityEmulatorTaskTest, PressureEmulatorTaskTest, TemperatureEmulatorTaskTest, HumidifierEmulatorTaskTest, HvacEmulatorTaskTest, LEDEmulatorTaskTest

### Integration Tests Executed

SensorEmulatorManagerTest, ActuatorEmulatorManagerTest

- 
- 
- 

EOF.
