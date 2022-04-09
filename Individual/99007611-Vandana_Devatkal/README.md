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

## Referance for Battery management

* https://in.mathworks.com/solutions/power-electronics-control/battery-management-system.html
* https://www.matlabcoding.com/2019/08/battery-management-system-development.html
* https://www.youtube.com/watch?v=ih0UyVc6sJA
* https://www.youtube.com/watch?v=0aISnkBu1k4
## Research papers

* A. C. R and A. Ghosh, "Battery Management System in Electric Vehicle," 2021 4th Biennial International Conference on Nascent Technologies in Engineering (ICNTE), 2021, pp. 1-6, doi: 10.1109/ICNTE51185.2021.9487762.
* https://evreporter.com/battery-management-system-for-electric-vehicles/#:~:text=BMS%20is%20an%20electronic%20system,and%20optimise%20the%20battery%20performance


## Use Case Diagram

![image](https://user-images.githubusercontent.com/66207959/160225210-3943ebd2-e612-4cb8-bddc-414ed768422b.png)

## Flow chart
![BMS Flow chart](https://user-images.githubusercontent.com/66207959/160229388-d20a838b-f4ad-40c6-be9d-0fa9500e40c7.png)

## Simulink Model
![Screenshot (743)](https://user-images.githubusercontent.com/66207959/160252440-7aa68752-1f8f-4b5d-9ce9-7548459ba348.png)

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

