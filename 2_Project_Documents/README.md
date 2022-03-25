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

## SWOT Analysis
![image](https://user-images.githubusercontent.com/66207959/160119689-b559561c-f66f-4d42-8eb5-f6c0c91f338e.png)


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
| LLR6 | Disturbance angle should be sensed | Deviation of the bike from the rest angle should be known for further calculation. |
### SWOT Analysis
![Algorithm flowchart example (2)](https://user-images.githubusercontent.com/98849909/160179631-7f6d65a0-8611-44c3-ad89-0b896118ba83.png)
### Usecase Diagram 
![Blank diagram (3)](https://user-images.githubusercontent.com/98849909/160179752-b84e5aee-759a-4e64-9790-e73ac9dbbf2d.png)
### Black Box
![team 5 functional structural (4)](https://user-images.githubusercontent.com/98849909/160179854-9bea707d-ffb3-40fa-b8de-0f21cdd89ba8.png)

# Lighting control system
  Today, electric vehicles are becoming increasingly popular. Small vehicle makers, as well as big automobile manufacturers, are developing electric vehicles. Electric vehicles are a state strategic plan for the next decade because of the environmental demands, the competence of local power electronics technology, and the tardy development of new internal combustion engine-based cars. Electric vehicles of all brands and sizes are now available on the market. New electric vehicle parts and components are being developed in the electric car arena.
  
  ## Requirements
  
  ### High Level Requirements:
| ID | Requirement |
| --- | --- |
|HLR01	|The Light should turn on automatically when the vehicle starts|
|HLR02	|The Right light should turn on when steering turned to words right|
|HLR03	|The Main Headlamp should turn on when the steering is straight|
|HLR04	|The Left light should turn on when steering turned to words left|

### Low Level reqirement
|LLR	|Description|
|-----|----------|
|LLR01	|If the vehicle turned on the light should turn on|
|LLR02	|If Value 10 is pressed the right light should turn on|
|LLR03	|If the vehicle turned on the light should turn on|
|LLR04 |If Value 20 is pressed the Left should turn on|

# Anti-Lock Braking System

## Abstract

The Anti-lock braking system is used in an application where there is a need for traction control between the wheel of the bike and the road when the brake is applied.
In traditional breaking system on applying the brakes, the wheel used to get locked and slip on the road resulting in losing control on the bike. To overcome this
problem ABS was introduced which provides intermittent braking of the wheel and facilitates good traction control. 
  
## Description

ABS uses speed sensors on the wheels to accurately determine the wheel speed as well as sensors to determine when a wheel is about to lock. Then, the ABS adjusts the
braking pressure accordingly using the combination of the electronic control unit (ECU) and pressure valves to prevent the wheel from locking and assists with
maintaining the stability of the bike.

## Identifying Features

* Takes the wheel speed input from speed sensor.
* Control the braking action based on the wheel’s speed input.

## Requirements

### High Level Requirements

| ID	|Description|
|-----|----------|
|HLR1|Control the braking action based on the speed senor’s input|
|HLR2|Reduce the stopping distance|

### Low Level Requirements

| ID	|Description| ID |
|-----|----------|-----|
|LLR1|Determining the wheel’s speed on braking (reduction/stopping the wheel)|HLR1|
|LLR2|Determining the vehicle’s speed on braking (reduction/stopping the vehicle)|HLR1|
|LLR3|Determining the relative slip between the wheel and the road|HLR1|
|LLR4|Determining the reduce in the slip distance on braking|HLR2|

## SWOT Analysis

![Screenshot (295)](https://user-images.githubusercontent.com/42509490/160194974-011710ee-e198-48da-a448-84c230893f24.png)

## 5W's and 1H

