# 📌Battery Management System

## Abstract

In electric vehicles, batteries are the primary source of power. The battery we use requires charging after few miles. So, in order to extract the maximum output of a battery and to ensure its safe operation it is necessary that an efficient battery management system is deployed in a vehicle.  It monitors the parameters, determine SOC, and provide necessary services to ensure safe operation of battery. Hence BMS form an important part of any electric vehicle.

## Description

BMS is an electronic system that manages a rechargeable battery to ensure it operates safely and efficiently. BMS is designed to monitor the parameters associated with the battery pack and its individual cells, apply the collected data to eliminate safety risks and optimise the battery performance.
* It performs the following operations:
* The system should monitor cell voltage
* The system should estimate the state of charge (SoC)
* The system should protect the battery from overcharge
* It should control the charging profile
* The system should monitor the temperature for thermal protection

## Requirements Modelling

### High Level Requirements

|Id| Requirements	|
|--|----------------|
|HLR 1 |The system should monitor cell voltage|	
|HLR 2 |The system should estimate the state of charge (SoC)|
|HLR 3|	The system should protect the battery from overcharge|
|HLR 4|	It should control the charging profile|	
|HLR 5|	The system should monitor the temperature for thermal protection|	

### Low Level Requirements

|Id|Requirements|
|--|------------|
|LLR 1|All cell voltages are measured in a lithium-ion pack|
|LLR 2|	SoC can be calculated by dividing the remaining capacity with total capacity.|
|LLR 3|	It shall limit the input and output power|
|LLR 4|By sensing the voltage at input, it shall control charging profile|
|LLR 5|Sensors are placed external to one or more cells per module and internal temperatures are calibrated.|

## Black Box

![Blank diagram](https://user-images.githubusercontent.com/66207959/160227172-7d996847-b189-4baf-ab87-9d68ebc80a3b.png)

## Block Diagram

![BMS Block Diagram](https://user-images.githubusercontent.com/66207959/160226990-ee70fbaf-58b9-426d-9cf1-42c4f0a53d68.png)

## SWOT Analysis

![image](https://user-images.githubusercontent.com/66207959/160119689-b559561c-f66f-4d42-8eb5-f6c0c91f338e.png)

## 5W and 1H

![image](https://user-images.githubusercontent.com/66207959/160224414-966ec5ea-3848-4bcc-86f5-6cb24daf130a.png)

## Use Case Diagram

![image](https://user-images.githubusercontent.com/66207959/160225210-3943ebd2-e612-4cb8-bddc-414ed768422b.png)

## Flow chart
![BMS Flow chart](https://user-images.githubusercontent.com/66207959/160229388-d20a838b-f4ad-40c6-be9d-0fa9500e40c7.png)

## Simulink Model
![Screenshot (743)](https://user-images.githubusercontent.com/66207959/160252440-7aa68752-1f8f-4b5d-9ce9-7548459ba348.png)
