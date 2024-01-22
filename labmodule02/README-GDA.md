# Gateway Device Application (Connected Devices)

## Lab Module 02

### Description

What does your implementation do? 

Built an application - GDA(Gateway Device Application) using Java . The application log the CPU utilization and Memory utilization and regular intervals using system logger.

How does your implementation work?

SystemPerformanceManager module in the applications uses handleTelemetry method to get the CPU and Memory utilization which is connected to GDA. SystemCpuUtilTask module returns the CPU utilization percentage and SystemMemUtilTask module returns the memory utilization memory to the SystemPerformanceManager. A background scheuler using apscheduler library schedules each task at regular intervals and logs the values.

### Code Repository and Branch

URL: https://github.com/Pradyumna36/PIOT-Java-Components/tree/labmodule02

### UML Design Diagram(s)

https://github.com/Pradyumna36/Book-Exercises-Doc/issues/2

### Unit Tests Executed

SystemCpuUtilTaskTest, SystemMemUtilTaskTest

### Integration Tests Executed

ConstrainedDeviceAppTest, SystemPerformanceManagerTest

EOF.
