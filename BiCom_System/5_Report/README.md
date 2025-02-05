﻿﻿# TABLE OF CONTENT
 |S.NO|CONTENT|
 |--|--|
 |1|BICOM SYSTEM|
 |1.1|Description|
 |1.2|Features|
 |1.3|5W's AND 1H |
 |1.4|SWOT Analysis|
 |2|REQUIREMENTS|
 |2.1|High level requirements|
 |2.2|Low level requirements|
 |3|ARCHITECTURE|
 |3.1|STRUCTURAL DIAGRAM|
 |3.1.1|High level structural diagram|
 |3.1.2|Low level structural diagram|
 |3.2|BEHAVIORAL DIAGRAM|
 |3.2.1|High level behavoiral diagram|
 |3.2.2|Low level behavoiral diagram|
 |4|TEST PLAN AND OUTPUT|
 |4.1|High level test plan|
 |4.2|Low level test plan|

# 1.BICOM SYSTEM

## 1.1.Description
* A BiCom systemis the extention of the unidirectional RKE to bidirectional RKE system. 

## 1.2.Features
* It shall print window status of the car when blue switch is pressed once
* It shall print alarm status of the car when blue switch is pressed twice
* It shall print car battery information when the blue switch is pressed thrice times
* It shall print door status of the car when the blue switch is pressed four times

# 1.3.5W's AND 1H

## WHat
- URemote wireless key for car/Automotives.

## Who 
- User Who wants to know status Remotely.

## Where
- When user is away/inside the car.

## When 
- To know status of window , alarm, battery ,door.

## Why 
- To know the status of features of the car.

## How
- Using switch by blinking the LEDis to know status of window, battery alarm,door.

# 1.4.SWOT Analysis

![cccccccc](https://user-images.githubusercontent.com/46950972/157836003-40a6c505-2664-4091-9a9f-f4c7c78e4f23.png)

## 2.REQUIREMENTS

### 2.1.High level requirements

| ID | Requirements |
|----|--------------|
|HLR1| It shall print window status of the car|
|HLR2|	It shall print alarm status of the car|
|HLR3|	It shall print car battery information|
|HLR4|	It shall door status of the car|

### 2.2.High level requirements

|ID	|Low Level Requirements for HLR1	|  |ID|	Low Level Requirements for HLR2|
|----|--------------------------------|--|----|--------------|
|LLR1.1|	If the switch is pressed once, ON all LED's| |	LLR2.1	|If the switch is pressed twice, OFF LED's|

|ID|	Low Level Requirements for HLR3|	|ID	|Low Level Requirements for HLR4|
|----|-------------------------------|--|----|--------------|
|LLR3.1|	If the switch is pressed three times, ON all LED's in clockwise manner	|  |	LLR4.1|	If the switch is pressed FOUR times, ON all LED's in anti-clockwise manner|

## 3.ARCHITECTURE
# 3.1.STRUCTURAL DIAGRAM

## 3.1.1.HIGH LEVEL STRUCTURAL DIAGRAM
![HIGHLEVEL](https://github.com/sowmyavnaik/M3_Group18/blob/main/BiCom_System/2_Archietecture/M3-SDHL.drawio.png)

## 3.1.2.LOW LEVEL STRUCTURAL DIAGRAM
![LOWLEVEL](https://github.com/sowmyavnaik/M3_Group18/blob/main/BiCom_System/2_Archietecture/M3-SDLLBI.drawio.png)

# 3.2.BEHAVIORAL DIAGRAM

## 3.2.1.HIGH LEVEL BEHAVIORAL DIAGRAM
![HIGHLEVEL](https://github.com/sowmyavnaik/M3_Group18/blob/main/BiCom_System/2_Archietecture/M3-hlbd.drawio.png)

## 3.2.2.LOW LEVEL BEHAVIORAL DIAGRAM
![LOWLEVEL](https://github.com/sowmyavnaik/M3_Group18/blob/main/BiCom_System/2_Archietecture/M3-llbd.drawio.png)

## 4.TEST PLAN AND OUTPUT
## 4.1.HIGH LEVEL TEST PLAN 

|Test|	Description|	Input|	Expected output|	Actual Output|
|----|-------------|--------|-------------------|--------------|
|01	|Window Status	|switch pressed once	| shall print window status of the car|	shall print window status of the car|
|02|	Alarm Status|	switch pressed twice|	shall print alarm status of the car|shall print alarm status of the car|
|03	|Car Battery Info|	switch pressed three times|	shall print car battery information|	shall print car battery information|
|04	|Door status|	switch pressed four times|	shall door status of the car|	shall door status of the car|

## 4.2.LOW LEVEL TEST PLAN

|Test|	Description|	Input|	Expected output|	Actual Output|
|----|-------------|--------|-------------------|--------------|
|01|	Window Status|	switch pressed once|	shall on all led's |shall on all led's	|
|02|	Alarm Status|	switch pressed twice	|shall off all led's| shall off all led's |
|03|	Car Battery Info| switch pressed three times	|shall on led's once clockwise|shall on led's once clockwise	|
|04|	Door status|	switch pressed four times	|shall on led's once anti-clockwise| shall on led's once anti-clockwise	|



