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

* Angle of Deviation
![Screenshot (750)](https://user-images.githubusercontent.com/66207959/160251669-bcf5eeca-969f-4151-a4d6-e64f42eeecae.png)

* Oscillations
<img width="479" alt="Self_balance" src="https://user-images.githubusercontent.com/98833151/160252826-3d9930ca-ba92-4bd8-9340-699301225fc6.png">

## Testing for Battery Management System

|Sl.No|Requirements|input|Expected output|Actual output|Status|
|-----|------------|---------------|-------------|-----|------|
|1|The system should monitor cell voltage|33V|Displays 33V|Display = 33V|PASS|
|2|The system should estimate the state of charge (SoC)|No input| 85%|85%|PASS|
|3|The system should monitor the temperature for thermal protection|41 degree celcius(from sensor)|41 degree celcius|41 degree celcius|PASS|
|4|The system should maintain the temperature to 48 degree celcius of the battery if increases|52 degree celcius|48 degree celcius|48 degree celcius|PASS|
### Charge percentage
![Screenshot (744)](https://user-images.githubusercontent.com/66207959/160251711-18bf956e-c20a-4714-95dd-d3ac206a6ecf.png)
### Current graph
![Screenshot (745)](https://user-images.githubusercontent.com/66207959/160251775-d0fbe685-cc48-492c-9d2c-464f1b73edf0.png)
### Voltage graph
![Screenshot (746)](https://user-images.githubusercontent.com/66207959/160251748-32c82c7f-033b-4e0c-ac95-a4da1cf7a159.png)
### Temperature graph
![Screenshot (747)](https://user-images.githubusercontent.com/66207959/160252649-ce35402a-06b6-4e0c-9255-4a15e8c81235.png)

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

## Output

![Screenshot (300)](https://user-images.githubusercontent.com/42509490/160251176-6bc619b2-f51b-4c34-94a4-7a81aa57b79a.png)

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



