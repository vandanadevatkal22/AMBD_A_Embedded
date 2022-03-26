# Testing

## Testing for Self-Balancing System

Rules: The system do not work when is speed is greater than 4 kmph which will display a read light and whenever the speed is less than 4 is will diplay a green light which means the system can be implemented and working
|Sl.NO| Input(Acceleration in kmph) | Input(Angular Deviation in degree) | Expected Output | Actual Output | Status |
|:---|:---|:---|:---|:----|:----|
|1. | 45 | 6 | Read light glowing | Read light glowing | PASS |
|2. | 30 | 4 | Read light glowing | Read light glowing | PASS |
|3. | 3  | 3 | Green light glowing | Green light glowing | PASS |
|4. | 2 | 7 | Green light glowing | Green light glowing | PASS |
|5. | -2 | 3 | Green light glowing | Green light glowing | PASS |
