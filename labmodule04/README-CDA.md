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

NOTE: Include one or more UML designs representing your solution. It's expected each
diagram you provide will look similar to, but not the same as, its counterpart in the
book [Programming the IoT](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401/).


### Unit Tests Executed

NOTE: TA's will execute your unit tests. You only need to list each test case below
(e.g. ConfigUtilTest, DataUtilTest, etc). Be sure to include all previous tests, too,
since you need to ensure you haven't introduced regressions.

- 
- 
- 

### Integration Tests Executed

NOTE: TA's will execute most of your integration tests using their own environment, with
some exceptions (such as your cloud connectivity tests). In such cases, they'll review
your code to ensure it's correct. As for the tests you execute, you only need to list each
test case below (e.g. SensorSimAdapterManagerTest, DeviceDataManagerTest, etc.)

- 
- 
- 

EOF.
