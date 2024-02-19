# Constrained Device Application (Connected Devices)

## Lab Module 03

### Description

What does your implementation do? 
Added simulation and actuation capabilities into CDA using a data generator to generate time-series data for humidity, pressure and temperature. The generator creates a data sets which are packaged as telemetry objects that contain additional information about the device. A threshold trigger issues an actuator command to the actuator simulator when the sensor value fall outside the threshold values.

How does your implementation work?
A simple data generator within the python-components repository is used to create time series data for the sensors. The DeviceDataManager handles all data processing within the application and sends the requests to appropriate destinations. It receives data from SensorAdapterManager and sends actuation commands to ActuatorAdapterManager. _handleSensorDataAnalysis() method checks if the sensor value is above the ceiling value or below the floor value and sends actuator command to turn ON HVAC if required.  

### Code Repository and Branch

NOTE: Be sure to include the branch (e.g. https://github.com/programming-the-iot/python-components/tree/alpha001).

URL: https://github.com/Pradyumna36/PIOT-Python-Components.git - LabModule03

### UML Design Diagram(s)

UML diagram - https://github.com/Pradyumna36/Book-Exercises-Doc/blob/labmodule03/labmodule03/CDA%20simulator%20UML.png

### Unit Tests Executed

ActuatorDataTest, BaseIotDataTest, SensorDataTest, SystemPerformanceDataTest, HumidifierActuatorSimTaskTest,
HumiditySensorSimTaskTest, HvacActuatorSimTaskTest, PressureSensorSimTaskTest, TemperatureSensorSimTaskTest

### Integration Tests Executed

DeviceDataManagerNoCommsTest, ActuatorAdapterManagerTest, SensorAdapterManagerTest

EOF.
