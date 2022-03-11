# Remote keyless Entry

Table of contents:
==================

<!--ts-->
   * 1.Description
   * 2.Requirements
      * 2.1)High Level Requirements
      * 2.2)Low Level Requirements
   * 3.SWOT Analysis
   * 4.5W's and 1'H
 <!--te--> 
  
### 1.Description:

![maxresdefault](https://user-images.githubusercontent.com/70833253/157854991-c6e073c1-658d-4d97-b77d-bd36b9dbdbbc.jpg)


Remote keyless entry(RKE) is a system designed to remotely lock or unlock access to automobiles.It operates by transmitting radio waves on a particular frequency.The main components required are the transmitter and the reciever.RKE system helps the vehicle from theft.It is a very usefull system nowadays.

### 2.Requirements:
#### 2.1) High Level Requirements:
| ID | Description |
| -- | --- |
| HLR-01 | UnLocking the Car -It shall turn ON all the Led’s on at the same time. |
| HLR-02 | Locking the Car -It shall turn OFF all the Led’s on at the same time. |
| HLR-03 | Alarm activation/deactivation -It shall turn On All Led’s in clockwise manner. |
| HLR-04 | Locking the Car -It shall turn OFF all the Led’s on at the same time. |
#### 2.2) Low Level Requirements:
| ID | Description |
| --- | --- |
| LLR01 | For single press- All lights ON |
| LLR02 | For double press- All lights OFF |
| LLR03 | For Pressing three times- All led ON in clockwise manner |
| LLR04 | For Pressing Four times- All led ON in anti-clockwise manner |
### 3.SWOT Analysis:
| SWOT | Description |
| --- | --- |
| Strength | Avoiding of theft |
| Weakness | Remote may not work at sometimes |
| Opportunity | Can be used in all the automobiles |
| Threat | If the remote is misses we cant open the car |
### 4. 5W's and 1H:

![file](https://user-images.githubusercontent.com/70833253/157871717-71d4f9a1-62e8-4200-a168-24fe3df3af51.jpg)

| W's and H | Description |
| --- | --- |
| What | Remote keyless entry |
| When | At the time of starting or ending the journey |
| Where | In automobiles |
| Who | For all the people who want to be theft free|
| Why | For easy use and to prvent theft |
| How | By pressing the buttons |

# User Case Diagram

![Untitled Diagram drawio (1)](https://user-images.githubusercontent.com/99134492/157879413-36f1e38c-b889-4e3a-a589-7c45254f874a.png)
















<img width="475" alt="Remote-Keyless-Entry-RKE-2" src="https://user-images.githubusercontent.com/70833253/157870330-c6de5d77-b1f3-4eab-b1a5-4039b7f93903.png">

# Testplan AND Output

## HIGH LEVEL TEST PLAN

|TestID|Description|Exp Input|Exp Output|Status|
|:-----|-----------|---------|----------|-----:|
|HL01|Remote Car Locking|switch pressed 1 time|Car Locked|Passing|
|HL02|Remote Car UnLocking|switch pressed 2 times |Car UnLocked|Passing|
|HL03|Alarm Activation|switch pressed 3 times|Alarm Activated|Passing|
|HL04|Alarm DeActivation|switch pressed 4 times|Alarm DeActivatedd|Passing|

## LOW LEVEL TEST PLAN

|TestID|Description|Exp Input|Exp Output|Status|
|:-----|-----------|---------|----------|-----:|
|LL01|All LEDs Should get turn ON together when Car is locked|switch pressed 1 time|All Leds are ON|Passing|
|LL02|All LEDs Should get turn OFF together when Car is unlocked|switch pressed 2 time|All Leds are OFF|Passing|
|LL03|Alarm Activation|switch pressed 3 times|LEDs turned ON one by one in clockwise direction|Passing|
|LL04|Alarm deactivation|switch pressed 4 time|LEDs turned OFF one by one in clockwise direction|Passing|


