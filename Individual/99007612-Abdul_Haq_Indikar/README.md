# 📌Self-Balancing System
## Description
In today's ever evolving market, competition for domination is increasing with the growth of market. In this market were the technology and use case keeps on growing, Rider's comfort plays an important role in selection of the Motorcycle. Riders often face difficulty in balancing motorcycles when riding at low speed in both the direction as many EV's today comes with reverse control and also when they are trying to stop, which further results in causing many accidents. Hence there is a need for Self-Balancing system in Motorcycles. </br> 
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
| LLR7 | The system should also work in both the direction | Self-balancing system should also work when the vehicle is in reverse gear |

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

### Simulink Model
![Screenshot (752)](https://user-images.githubusercontent.com/66207959/160252450-00241479-53b9-4490-96e6-c23b4b09751f.png)
