# TABLE OF CONTENTS

1. [ABSTRACT](#1-abstract)
2. [DESCRIPTION](#2-description)
3. [REQUIREMENTS](#3-requirements)
    
    3.1. [HIGH LEVEL REQUIREMENTS](#31-high-level-requirements)
   
    3.2. [LOW LEVEL REQUIREMENTS](#32-low-level-requirements)
 
4. [SWOT ANALYSIS](#4-swot-analysis)
5. [4W and 1H](#5-4w-and-1h)

## 1 ABSTRACT

Often in the modern day world we have seen vehicles which no more require an entry key to turn on the vehicle. This highlights the mechanism of remote keyless system which unlocks the doors, and a remote keyless ignition system (RKI), which starts the engine.The system signals that it has either locked or unlocked the car usually through some fairly discreet combination of flashing vehicle lamps, a distinctive sound other than the horn, or some usage of the horn itself. A typical setup on cars is to have the horn or other sound chirp twice to signify that the car has been unlocked, and chirp once to indicate the car has been locked. The functions of a remote keyless entry system are contained on a key fob or built into the ignition key handle itself. Buttons are dedicated to locking or unlocking the doors and opening the trunk or tailgate. 

On some mini vans, the power sliding doors can be opened/closed remotely. Some cars will also close any open windows and roof when remotely locking the car. Some remote keyless fobs also feature a red panic button which activates the car alarm as a standard feature.
# 2 DESCRIPTION
Remote keyless entry (RKE) system is a system designed to remotely lock or unlock access to automobiles. 
1. RKE transmission requires two components - a transmitter and a receiver. 
   * Transmitter - RKE key fob, other ID device with RKE integrated 
   * Receiver - Body Control ECU, other ECU with integrated RKE 
2.	RKE operates by broadcasting radio waves on a particular frequency unidirectionally. 
3.	RKE systems implement encryption and rolling code algorithms to prevent car thieves from intercepting and spoofing the telegrams. 
4.	Typical RKE functions are: 	Print lock – (Blue switch on- All led on at the same time)
    * Print unlock - (Blue switch press two times- All led off at the same time)
    * Print alarm activation/deactivation - (Blue switch press three times- All led on in clockwise manner)
    * Print approach light - (Blue switch press four times- All led on in anti-clockwise manner)


# 3 REQUIREMENTS

## 3.1 HIGH LEVEL REQUIREMENTS

|S.NO| REQUIREMENTS|WORKING|
|----|-------------|-------|
|HLR01| SINGLE PRESS SHOULD LOCK THE DOOR|YES|
|HLR02| DOUBLE PRESS SHOULD UNLOCK THE DOOR|YES|
|HLR03| THREE TIMES PRESS SHOULD ACTIVATE/DEACTIVATE THE ALARM SYSTEM IN THE CAR|YES|
|HLR04| PRESSING THE KEY FOR FOUR TIMES SHOULD START THE APPROACH LIGHT OF THE CAR|YES|

## 3.2 LOW LEVEL REQUIREMENTS

|S.NO| REQUIREMENTS|WORKING|
|----|-------------|-------|
|LLR01|IF USER INPUT IS PRESSED ONCE, ALL 4 LED SHOULD TURN ON SIMULTANEOUSLY|YES|
|LLR02|IF USER INPUT IS PRESSED TWICE, ALL 4 LED SHOULD TURN OFF SIMULTANEOUSLY|YES|
|LLR03|IF USER INPUT IS PRESSED THRICE, ALL 4 LED SHOULD TURN ON IN CLOCKWISE MANNER (GREEN->ORANGE->RED->BLUE)|YES|
|LLR04|IF USER INPUT IS PRESSED FOUR TIMES, ALL 4 LED SHOULD TURN ON IN ANTI-CLOCKWISE MANNER (BLUE->RED->ORANGE->GREEN)|YES|

# 4 SWOT ANALYSIS

## STRENGTH
* Remote Starting
* Time is saved during urgent situation
* Support for Effecient operation.

## WEAKNESS
* cost of system may be increased
* complex System
* issues of engine running after parking the car
* Beyond the certain distance we can't unlock or lock it.

## OPPORTUNITIES
* Advancement in Technology.
* It can provide to not only large automobiles but also for small ones when there is theft of vehicles.

## THREAT
* Targated Attacks
* Identity Theft

#  4W And 1H

## Who???

* This system is used by people to lock/unlock car

## What???

* This is an keyless entry which can lock/unlock the cars without Mechanical key

## When???

* This system can be used whenever there is the need of locking/unlocking of car

## Where???

* This System can be used in Automotives

## How???

* This system works on buttons when lock button is pressed the car locks and if unlock button is pressed the car unlocks.
