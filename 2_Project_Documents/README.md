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
 
# Self-Balancing System
## Description
In today's ever evolving market, competition for domination is increasing with the growth of market. In this market were the technology and use case keeps on growing, Rider's comfort plays an important role in selection of the Motorcycle. Riders often face difficulty in balancing motorcycles when riding at low speed or when trying to stop, which further results in causing many accidents. Hence there is a need for Self-Balancing system in Motorcycles. </br> 
Self-balancing System works on the principle of Conservation of Angular Momentum. Which uses a flywheel for countering the momentum which may result in fall of motorcycle.
## Requirements
### High Level Requirements:
| ID | Requirement | Description |
| --- | --- | --- |
| HLR1 | Self-Balancing System should get activated when the speed is Low | The system Should always sense the speed of motorcycle and should get activated when the speed is below the set(threshold) value. |
| HLR2 | Self-Balancing System should balance the motorcycle | The system should be capable enough to balance the motorcycle |
| HLR3 | Self-Balancing System should get deactivate when the speed is high | The system should always sense the sped of motorcycle and self-balancing feature should get deactivated when the speed is higher than the set(threshold) value |
### Low Level Requirements:
| ID | Requirement | Description |
| --- | --- | --- |
| LLR1 | Sensing the speed | The system should be able to always sense the speed of the motorcycle so as to perform certain decision making. |
| LLR2 | Decision making regarding the activation and deactivation of Self-Balancing system. | The system should have a proper decision-making capability to decide when to activate or deactivate the self-balancing system. |
| LLR3 | Set value should be defined clearly | Set value or threshold value which is used to decide the self-balancing mode should be defined. |
| LLR4 | A Feedback loop should be established | The system should have a working feedback loop to send the current data back to the control loop |
| LLR5 | A controller/Control Unit should be created | A controller should be created for calculating the counter momentum to be made |
| LLR6 | Disturbance angle should be sensed | Deviation of the bike from the rest angle should be known for further calculation |
