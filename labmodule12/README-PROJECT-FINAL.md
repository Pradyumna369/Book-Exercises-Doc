# Lab Module 12 - Semester Project - Final Write-up

NOTE: Be sure to implement all the Lab Module 12 requirements listed at [Lab Module 12](https://github.com/orgs/programming-the-iot/projects/1#column-10488565).


## Description

The project idea is Home Environment Monitoring and Temperature Adjustment.It which aims at monitoring and maintaining the temperature and humidity in home at optimal comfortable levels.



## What - The Problem 

The project aims to solve the problem of uncomfortable home environments and high energy bills by automatically adjusting factors like temperature and humidity. By doing this, it makes homes more pleasant to live in while also helping people save money and reduce their energy usage. This is important because everyone wants to feel comfortable in their own home, and saving energy is good for the environment too.



## Why - Who Cares? 

Many people care about this, including homeowners who want to feel cozy at home, companies that build houses, and those who want to protect the environment. Making homes more comfortable and energy-efficient can improve people's quality of life and reduce their impact on the planet. Plus, it's a win-win situation because it saves money on energy bills as well.



## How - Expected Technical Approach

The project will utilize a constrained device application, gateway device application and cloud service. CDA will be responsible for monitoring temperature, humidity changes and triggering HVAC events. GDA will be receive data from CDA and sending actuation commands when the temperature and humidity levels falls outside predefined threshold limits. Cloud services will be used to store data and showing data in dashboard. MQTT protocol will be used for communication between CDA, GDA and cloud service.


### System Diagram

Embed a block diagram depicting your overall design, including the CDA, GDA, and Cloud Services interactions.
Be sure to include arrows depicting data flow from one application / service to the next.



Write 1 to 2 paragraphs describing your design.

High level diagram: https://github.com/Pradyumna369/Book-Exercises-Doc/blob/main/labmodule12/image.png



### What THREE (3) sensors and ONE (1) actuator did you use (add more if you wish)?

- CDA Sensor 1: Temperature sensor

- CDA Sensor 2: Humidity sensor

- CDA Sensor 3: Pressure sensor

- CDA Actuator 1: Led actuator



### What ONE (1) CDA protocol and TWO (2) GDA protocols did you implement (add more if you wish)?

- CDA to GDA Protocol: Mqtt protocol

- GDA to CDA Protocol: Mqtt protocol

- GDA to Cloud Protocol: Mqtt protocol

- Cloud to GDA Protocol: Mqtt protocol


 
### What TWO (2) cloud services / capabilities did you use (add more if you wish)?

- Cloud Service 1 (data ingress - all inputs): Ubidots

- Cloud Service 2 (data egress - all actuation events):



## Screen Shots Representing Cloud Services



### Screen Shots Representing Visualized Data

NOTE: Include (at least) TWO (2) screen shots - one showing at least 1 hour
of time-series data from the CDA, and one showing an event being triggered
that results in an actuation event sent to your GDA and then to your CDA.



EOF.
