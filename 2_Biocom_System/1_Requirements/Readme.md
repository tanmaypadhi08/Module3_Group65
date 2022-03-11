# DESCRIPTION

A BiCom system is the extention of the unidirectional RKE to bidirectional RKE system. Here it is similar to RKE where it is used for locking and unlocking of automobiles but there it is only of unidirectional but here it is used as bidirectional means here BiCom operates by radio waves on a particular frequency bidirectionally unlike RKE where it acts unidirectionally here it also provide entire car status on a LED where we can manage all the operations of an automobile.
   * keyfob -> car (like a unidirectional RKE system) 
   * car -> keyfob (car status information for displaying on the keyfob by LED or display) 
Typical BiCom status information transmitted to the keyfob are: 
  * Print window status (Blue switch on- All led on at the same time)
  * Print alarm status - (Blue switch press two times- All led off at the same time
  * Print car battery info – (Blue switch press three times- All led on in clockwise manner)
  * Print Door status (Blue switch press four times- All led on in anti-clockwise manner)
 
 # Requirements

## High level requirements:

|RID	|DESCRIPTION |
|---- |----|
|HLR1	|It shall check window status  |
|HLR2	|It shall check alarm status |
|HLR3	|It shall get the battery information |
|HLR4	|It shall check the door status |


## Low Level Requirement:

|RID	|DESCRIPTION |
|---- |----|
|LLR1 |The system should check window status when blue switch is pressed once|
|LLR2 |The system should check alarm status when the blue switch is pressed twice|
|LLR3 |The system should shall get the battery information when the blue switch is pressed three times|
|LLR4 |The system should check the door status when the blue switch is pressed four times|


 
 # SWOT ANALYSIS

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
* Targeted Attacks
* Identify Theft

# 4W's And 1H

## Who???

* This system is used by people to lock/unlock car

## What???

* This is an keyless entry which can lock/unlock the cars without mechanical key

## When???

* This system can be used whenever there is the need of locking/unlocking of car 

## Where???

* This System can be used in Automotives

## How???

* This system works on buttons when lock button is pressed the car locks and if unlock button is pressed the car unlocks

