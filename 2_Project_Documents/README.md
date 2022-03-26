# Battery Management System

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
### 5W and 1H
![image](https://user-images.githubusercontent.com/66207959/160225521-a8d6314d-dca8-4465-8748-712c7446e3e4.png)
### SWOT Analysis
![Algorithm flowchart example (2)](https://user-images.githubusercontent.com/98849909/160179631-7f6d65a0-8611-44c3-ad89-0b896118ba83.png)
### Usecase Diagram 
![Blank diagram (3)](https://user-images.githubusercontent.com/98849909/160179752-b84e5aee-759a-4e64-9790-e73ac9dbbf2d.png)
### Black Box
![team 5 functional structural (4)](https://user-images.githubusercontent.com/98849909/160179854-9bea707d-ffb3-40fa-b8de-0f21cdd89ba8.png)
### Flowchart
![Algorithm flowchart example](https://user-images.githubusercontent.com/98849909/160224994-83869859-5964-426a-9cba-8fe59ef87fb4.png)


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

## SWOT Analysis

![Amazon SWOT Analysis](https://user-images.githubusercontent.com/46382398/160226891-e3004ba1-23a5-4969-b63d-8641f3af7bf1.png)



## Flow chart (Automatic Head Lamp)

![flowchart_light](https://user-images.githubusercontent.com/46382398/160220662-d942d373-475b-4ede-afed-9d862c2b9031.png)

## Indicator system
![flowchart_light](https://user-images.githubusercontent.com/46382398/160221133-a1361b26-15fc-480d-9414-84878f1a1cc8.png)


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

## Black Box

![Screenshot (296)](https://user-images.githubusercontent.com/42509490/160197020-7e2688b5-e9bd-4ca1-a322-6e37bb142a69.png)

## Flowchart

![Screenshot (297)](https://user-images.githubusercontent.com/42509490/160228019-1a506cc7-bbfd-4896-8506-acdf8ec7ac38.png)

## SWOT Analysis

![Screenshot (295)](https://user-images.githubusercontent.com/42509490/160194974-011710ee-e198-48da-a448-84c230893f24.png)

## 5W's And 1H

![Screenshot (298)](https://user-images.githubusercontent.com/42509490/160229128-0d39030b-e1c7-4cd7-9635-077e52b840ff.png)


# Speed Modes

## Abstract

Speed modes can alter the sensitivity of the throttle, the amount of fuel going into the engine, the amount of traction available and variations on the suspension settings. These variations may alter in conjunction or separately to bring about changes in how the bike rides and feels.

## Introduction

Most modern vehicles are controlled by an Engine Control Unit (ECU) a sophisticated system that can control the vehicles’s main components including engine transmission, suspension, steering and braking. This has allowed automobile manufacturers to offer different driving modes that change the handling, dynamics and efficiency of a vehicle at the touch of a button. This has essentially enabled manufacturers to offer one vehicle that can fulfil multiple roles more seamlessly. For example, when on your commute, you may wish to be in the most efficient drive mode setting to ensure the best fuel efficiency. However, on a long journey, you may prefer quicker responses and better performance from your vehicle. Thanks to different driving modes, this is now all possible from just one vehicle.

### Eco Mode:
Eco mode is designed to reduce fuel consumption and improve the bike’s efficiency. To achieve this, the amount of fuel allowed into the engine is often reduced, and some of the engine cylinders may be shut down. The throttle response often reduces to help the driver use less fuel and improve mileage capabilities, but this can make the bike feel slower.

### Urban Mode:
It offers the ideal setting for long commutes as it helps make sure the bike runs as smoothly and comfortably as possible. It offers a good balance between Eco and Sport settings and is ideal for day-to-day use. The suspension is usually in its softest setting to help smooth out any bumps or jolts in the road, while in automatics the gear changes may come earlier to allow for a smoother and steadier ride-quality.   

### Sports Mode:
In sports mode, the throttle will become more responsive, meaning the bike accelerates more readily. In addition, more fuel is introduced into the engine to increase the available power, the steering gets heavier and the suspension will stiffen. 

## Requirement Modelling

### High Level Requirements

|ID|Description|
|:---|:---|
|HLR 1 |The system shall turn ON.|	
|HLR 2 |The system shall turn OFF.|
|HLR 3|	The system shall switch to Self balance mode.|
|HLR 4|	The system shall switch to Eco mode.|	
|HLR 5|	The system shall switch to Urban mode.|
|HLR 6| The system shall switch to Sports mode.|

### Low Level Requirements

|ID|Description|HLRID|
|:---|:---|:---|
|LLR1|The system shall turn ON when the input given is HIGH(1).|HLR1|
|LLR2|The system shall turn OFF when the input given is LOW(0).|HLR2|
|LLR3|The system is in self balance mode only when input is high and turns off when mode/input is changed.|HLR3|
|LLR4|The system is in eco mode only when the input is 2.|HLR4|
|LLR5|The system is in urban mode only when the input is 3.|HLR5|
|LLR6|The system is in sports mode only when the input is 4.|HLR6|

