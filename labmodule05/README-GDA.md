# Gateway Device Application (Connected Devices)

## Lab Module 05

### Description

What does your implementation do? 
Building data management and integration capabilities to GDA by building a converter to serialize and
deserialize data wrappers from/to JSON. Created data containers for sensor data, actuator data, system performance data which are derived from BaseIotData 

How does your implementation work?
Used gson Json parser in the DataUtil class to convert the actuator data, sensor data and system performance data to JSON and vice versa

### Code Repository and Branch

URL: https://github.com/Pradyumna36/PIOT-Java-Components/tree/labmodule05

### UML Design Diagram(s)

https://github.com/Pradyumna36/Book-Exercises-Doc/blob/labmodule05/labmodule05/GDA_Data_Management_UML.png

### Unit Tests Executed

ActuatorDataTest, SensorDataTest, SystemPerformanceDataTest, DataUtilTest

### Integration Tests Executed

SystemPerformanceManagerTest, DataIntegrationTest, DeviceDataManagerNoCommsTest, GatewayDeviceAppTest


EOF.
