# Bi Communication System
## Requirements:
### Description:
Bi Communication system is the extension of the unidirectional Remote Keyless Entry(RKE) system.It is the advanced system of RKE.In this system we can check the status of the car in the keyfob by means of LED or by means of display in the remote.In this also we use radiowaves.It is very much usefull then RKE system.We call it as bi communication system,because in ths remote give the input to the car and the car give input to the remote or keyfob. 
### High Level Requirements:
| ID | Description |
| --- | --- |
| HLR01 | Able to open or close the door |
| HLR02 | Able to on or off the engine |
| HLR03 | Able to see the status of the battery |
| HLR04 | Able to see the status of the doors and windows |
### Low Level Requirements:
| ID | Description |
| --- | --- |
| LLR01 | View the location of the car |
| LLR02 | On or off the multimedia inside the car |
| LLR03 | View multimedia is working or not |
### SWOT analysis:
| SWOT | Description |
| --- | --- |
| Strength | Avoiding of theft and we can able to check the status of the car |
| Weakness | Key fob may not work if water splashes on it |
| Opportunity | Can be used in all automobiles |
| Threat | If the remote breaks it may lead to missfunctions |
### 4W's and 1H
| W's and H | Description |
| --- | --- |
| What | Bi communication system |
| Why | To control the automobile easily |
| When | Before starting the journey and at the end of the journey |
| Where | All automobile |
| How | By remote control |


# **2 ARCHITECTURE**

# 2.1 Behavioural Diagrams

## High Level Diagram
![behav-highlevel flow](https://user-images.githubusercontent.com/99134492/157885602-8ca8eda6-f741-4803-9dbb-6f2a334cf509.png)
## Low level diagram 

![behave_lowlevel_flow](https://user-images.githubusercontent.com/99134492/157887799-9dbe8509-7e6a-4a9b-bc7b-62baa47601f7.png)


# 2.2 Structural Diagram

## User Case Diagram
![Untitled Diagram drawio (1)](https://user-images.githubusercontent.com/99134492/157879413-36f1e38c-b889-4e3a-a589-7c45254f874a.png)


## Low level Diagram

![STRURAL-low LEVEL DIAGRAM](https://user-images.githubusercontent.com/99134492/157897587-dedf5be4-6693-45f5-a7b5-5aac54a0be62.png)



# Test Plan
## High Level Test:
|Test id |Description |expected i/p |expected o/p |Actuall o/p |pass/fail |            
|---- |---- |---- |---- |----|----|
|HLT1 |window status  |switch is pressed |window status display |window status display |pass |
|HLT2 |alarm status |switch is pressed |alarm status displayed |alarm status displayed  |pass |
|HLT3 |car battery info  |Switch is pressed |car battery info displayed |car battery info displayed |pass |
|HLT4 |Door status |Switch is pressed |Door status displayed |Door status displayed |pass |


## Low Level Test:


|Test id |Description |expected i/p |expected o/p |Actuall o/p |pass/fail |
|---- |---- |---- |---- |----|----|
|LLT1 |test for window status |Switch is pressed |All the led's are turned ON at same time  |All the led's are turned ON at same time |pass |  
|LLT2 |test for alarm status  |Switch is pressed Twice |All the led's are turned OFF at same time  |All the led's are turned OFF at same time |pass |  
|LLT3 |test for car battery info |Switch is pressed Thrice |All the led's are turned ON in clockwise direction  |All the led's are turned ON in clockwise direction  |pass | 
|LLT4 |test for Door status|Switch is pressed 4 times |All the led's are turned ON in anticlockwise direction  |All the led's are turned ON in anticlockwise direction  |pass |



