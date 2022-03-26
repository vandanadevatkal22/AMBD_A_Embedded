# Testing

## Testing for Self-Balancing System

Rules: The system do not work when speed is greater than 4 kmph which will display a read light and whenever the speed is less than 4 is will diplay a green light which means the system can be implemented and working
|Sl.NO| Input(Acceleration in kmph) | Input(Angular Deviation in degree) | Expected Output | Actual Output | Status |
|:---|:---|:---|:---|:----|:----|
|1. | 45 | 6 | Read light glowing | Read light glowing | PASS |
|2. | 30 | 4 | Read light glowing | Read light glowing | PASS |
|3. | 3  | 3 | Green light glowing | Green light glowing | PASS |
|4. | 2 | 7 | Green light glowing | Green light glowing | PASS |
|5. | -2 | 3 | Green light glowing | Green light glowing | PASS |


## Testing for Battery Management System

|Sl.No|Requirements|input|Expected output|Actual output|Status|
|-----|------------|---------------|-------------|-----|------|
|1|The system should monitor cell voltage|33V|Displays 33V|Display = 33V|PASS|
|2|The system should estimate the state of charge (SoC)|No input| 85%|85%|PASS|
|3|The system should monitor the temperature for thermal protection|41 degree celcius(from sensor)|41 degree celcius|41 degree celcius|PASS|
|4|The system should maintain the temperature to 48 degree celcius of the battery if increases|52 degree celcius|48 degree celcius|48 degree celcius|PASS|



## Testing for Lighting system

|SL No|	Description| Exp I/P | Exp O/P | Actual o/P|  Type of Test | status|
|----|---|-----|------|---------|-------|--------| 
|01	|If the vehicle turned on the light should turn on| 1 | Head Light On | Head Lamp  on | Requirement Based | Pass|
|02	|If Value 10 is pressed the right light should turn on| 10 | Right Indictor On | Right Indicator On | Requirement Based | Pass|
|03	|If the vehicle turned on the light should turn on| 1 | Head Light On | head Lamp on | Requirement Based | Pass |
|04 |If Value 20 is pressed the Left should turn on| 20 |Left Indicator on | Left indicator on | Requirement Based | Pass |

## Testing for Anti-Lock Braking System

|SL No|Description|Input|Expected O/P|Actual O/P|Status|
|-----|------------|------------|------------|---------|----------|
|01|Determining the wheel’s speed on braking (reduction/stopping the wheel)|Signal builder input = Wheel slip (0.1 to 0.55) | Corresponding graphical output|Corresponding graphical output| Pass |
|02|Determining the vehicle’s speed on braking (reduction/stopping the vehicle)|Signal builder input = Wheel slip (0.1 to 0.55)| Corresponding graphical output|Corresponding graphical output| Pass | 
|03|Determining the relative slip between the wheel and the road|Signal builder input = Wheel slip (0.1 to 0.55)| Corresponding graphical output|Corresponding graphical output| Pass | 
|04|Determining the reduce in the slip distance on braking| Signal builder input = Wheel slip (0.1 to 0.55)| Corresponding graphical output|Corresponding graphical output| Pass | 

## Testing for Speed Modes

|SL No|Description|Input|Expected O/P|Actual O/P|Status|
|:---|:---|:---|:---|:---|:---|
|01|Determining whether the system is ON|USER input 1|Display Output 1|Display Output 1| ✅ |
|02|Determining whether the system is OFF|USER input 0|Display Output 0|Display Output 0| ✅ | 
|03|Determining the self-balancing mode|USER input 1|Display the speed range upto 14km/hr|Display the speed range upto 14km/hr| ✅ | 
|04|Determining the eco mode|USER input 2|Display the speed range upto 30km/hr|Display the speed range upto 30km/hr| ✅ |
|05|Determining the self-balancing mode|USER input 3|Display the speed range upto 65km/hr|Display the speed range upto 65km/hr| ✅ |
|06|Determining the self-balancing mode|USER input 4|Display the speed range upto 100km/hr|Display the speed range upto 100km/hr| ✅ |
