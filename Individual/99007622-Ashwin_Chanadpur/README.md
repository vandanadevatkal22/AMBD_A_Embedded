# 📌SPEED MODES

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

|ID|Description|HLR ID|
|:---|:---|:---|
|LLR1|The system shall turn ON when the input given is HIGH(1).|HLR1|
|LLR2|The system shall turn OFF when the input given is LOW(0).|HLR2|
|LLR3|The system is in self balance mode only when input is high and turns off when mode/input is changed.|HLR3|
|LLR4|The system is in eco mode only when the input is 2.|HLR4|
|LLR5|The system is in urban mode only when the input is 3.|HLR5|
|LLR6|The system is in sports mode only when the input is 4.|HLR6|

## SWOT Analysis

<img width="667" alt="SWOT_Speedmodes" src="https://user-images.githubusercontent.com/98833151/160239235-cf11f600-7f85-463b-bcc1-dd73aeb623ce.png">

## 5W's & 1H

<img width="547" alt="5W1H" src="https://user-images.githubusercontent.com/98833151/160239432-1aed2f65-3993-4150-8361-cd68bc5f873b.png">

## Black Box

<img width="541" alt="black box" src="https://user-images.githubusercontent.com/98833151/160238372-4d11c2d3-4665-400e-9283-c0c8f5a1a956.png">

## UseCase Diagram

![UseCase_org](https://user-images.githubusercontent.com/98833151/160245903-3131fce5-5df5-47a8-a7a4-cd8d0b1d4a30.png)

## Flowchart

<img width="401" alt="Speed_mode_flowchart" src="https://user-images.githubusercontent.com/98833151/160244500-77720124-cde7-41ca-bb3b-1567979c85c0.png">

## Testing for Speed Modes

|SL No|Description|Input|Expected O/P|Actual O/P|Status|
|:---|:---|:---|:---|:---|:---|
|01|Determining whether the system is ON|USER input 1|Display Output 1|Display Output 1| ✅ |
|02|Determining whether the system is OFF|USER input 0|Display Output 0|Display Output 0| ✅ | 
|03|Determining the self-balancing mode|USER input 1|Display the speed range upto 14km/hr|Display the speed range upto 14km/hr| ✅ | 
|04|Determining the eco mode|USER input 2|Display the speed range upto 30km/hr|Display the speed range upto 30km/hr| ✅ |
|05|Determining the self-balancing mode|USER input 3|Display the speed range upto 65km/hr|Display the speed range upto 65km/hr| ✅ |
|06|Determining the self-balancing mode|USER input 4|Display the speed range upto 100km/hr|Display the speed range upto 100km/hr| ✅ |

### Outputs:

* Self-Balance Mode

<img width="919" alt="Self_balance_mode" src="https://user-images.githubusercontent.com/98833151/160252858-2865ac02-ab14-4439-847e-4c5b3a3a8170.png">

* Eco Mode

<img width="913" alt="Eco_Mode" src="https://user-images.githubusercontent.com/98833151/160252859-298ae37f-35aa-4203-9de5-47b5ca1f2ad0.png">

* Urban Mode

<img width="908" alt="Urban_mode" src="https://user-images.githubusercontent.com/98833151/160252860-0d005c26-81b3-4e54-ae29-ba9e96a89687.png">

* Sports Mode

<img width="907" alt="Sports_mode" src="https://user-images.githubusercontent.com/98833151/160252867-27db5247-099d-4992-8452-8b693f053e1e.png">


## Reference for Speed Modes features:

* https://in.mathworks.com/help/physmod/sps/powersys/ug/simulating-variable-speed-motor-control.html
 
* https://www.youtube.com/watch?v=93Ry3Q4_yXk&ab_channel=SimulinkTutorial

## Research Papers

* https://www.researchgate.net/publication/335081177_Design_of_PMSM_Speed_Control_system_based_on_simulink_Model
