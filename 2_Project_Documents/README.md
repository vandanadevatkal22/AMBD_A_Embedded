# Battery Management System

## Abstract
In electric vehicles, batteries are the primary source of power. The battery we use requires charging after few miles. So, in order to extract the maximum output of a battery and to ensure its safe operation it is necessary that an efficient battery management system is deployed in a vehicle.  It monitors the parameters, determine SOC, and provide necessary services to ensure safe operation of battery. Hence BMS form an important part of any electric vehicle.

## Description

BMS is an electronic system that manages a rechargeable battery to ensure it operates safely and efficiently. BMS is designed to monitor the parameters associated with the battery pack and its individual cells, apply the collected data to eliminate safety risks and optimise the battery performance.
•	It performs the following operations:
•	The system should monitor cell voltage
•	The system should estimate the state of charge (SoC)
•	The system should protect the battery from overcharge
•	It should control the charging profile
•	The system should monitor the temperature for thermal protection

## Requirements Modelling

|Id|	High Level Requirements	|Low Level Requirements|
|--|----------------------------|----------------------|
|1 |The system should monitor cell voltage|	All cell voltages are measured in a lithium-ion pack|
|2 |The system should estimate the state of charge (SoC)|	SoC can be calculated by dividing the remaining capacity with total capacity.|
|3|	The system should protect the battery from overcharge|	It shall limit the input and output power|
|4|	It should control the charging profile|	By sensing the voltage at input, it shall control charging profile|
|5|	The system should monitor the temperature for thermal protection|	Sensors are placed external to one or more cells per module and internal temperatures are calibrated.|
 
