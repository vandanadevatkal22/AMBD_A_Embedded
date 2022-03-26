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
|-----|------------|---------------|-------------|------|
|1|The system should monitor cell voltage|33V|Displays 33V|Display = 33V|PASS|
|2|The system should estimate the state of charge (SoC)|No input| 85%|85%|PASS|
|3|The system should monitor the temperature for thermal protection|41 degree celcius(from sensor)|41 degree celcius|41 degree celcius|PASS|
|4|The system should maintain the temperature to 48 degree celcius of the battery if increases|52 degree celcius|48 degree celcius|48 degree celcius|PASS|
