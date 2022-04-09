# 📌Anti-Lock Braking System

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

## Simulation Model

![Screenshot (302)](https://user-images.githubusercontent.com/42509490/160253236-3ea587c9-4d97-48d4-95e7-634ee1d126b9.png)

## Testing for Anti-Lock Braking System

|SL No|Description|Input|Expected O/P|Actual O/P|Status|
|-----|------------|------------|------------|---------|----------|
|01|Determining the wheel’s speed on braking (reduction/stopping the wheel)|Signal builder input = Wheel slip (0.1 to 0.55) | Corresponding graphical output|Corresponding graphical output| Pass |
|02|Determining the vehicle’s speed on braking (reduction/stopping the vehicle)|Signal builder input = Wheel slip (0.1 to 0.55)| Corresponding graphical output|Corresponding graphical output| Pass | 
|03|Determining the relative slip between the wheel and the road|Signal builder input = Wheel slip (0.1 to 0.55)| Corresponding graphical output|Corresponding graphical output| Pass | 
|04|Determining the reduce in the slip distance on braking| Signal builder input = Wheel slip (0.1 to 0.55)| Corresponding graphical output|Corresponding graphical output| Pass | 

## Output

![Screenshot (300)](https://user-images.githubusercontent.com/42509490/160251176-6bc619b2-f51b-4c34-94a4-7a81aa57b79a.png)
