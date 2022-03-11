# DESCRIPTION
Remote keyless entry (RKE) system is a system designed to remotely lock or unlock access to automobiles. 
1. RKE transmission requires two components - a transmitter and a receiver. 
•	Transmitter - RKE key fob, other ID device with RKE integrated 
•	Receiver - Body Control ECU, other ECU with integrated RKE 
2.	RKE operates by broadcasting radio waves on a particular frequency unidirectionally. 
3.	RKE systems implement encryption and rolling code algorithms to prevent car thieves from intercepting and spoofing the telegrams. 
4.	Typical RKE functions are: 	Print lock – (Blue switch on- All led on at the same time)
    * Print unlock - (Blue switch press two times- All led off at the same time)
    * Print alarm activation/deactivation - (Blue switch press three times- All led on in clockwise manner)
    * Print approach light - (Blue switch press four times- All led on in anti-clockwise manner)


# REQUIREMENTS

## HIGH LEVEL REQUIREMENTS

|S.NO| REQUIREMENTS|WORKING|
|----|-------------|-------|
|HLR01| SINGLE PRESS SHOULD LOCK THE DOOR|YES|
|HLR02| DOUBLE PRESS SHOULD UNLOCK THE DOOR|YES|
|HLR03| THREE TIMES PRESS SHOULD ACTIVATE/DEACTIVATE THE ALARM SYSTEM IN THE CAR|YES|
|HLR04| PRESSING THE KEY FOR FOUR TIMES SHOULD START THE APPROACH LIGHT OF THE CAR|YES|

## LOW LEVEL REQUIREMENTS

|S.NO| REQUIREMENTS|WORKING|
|----|-------------|-------|
|LLR01|IF USER INPUT IS PRESSED ONCE, ALL 4 LED SHOULD TURN ON SIMULTANEOUSLY|YES|
|LLR02|IF USER INPUT IS PRESSED TWICE, ALL 4 LED SHOULD TURN OFF SIMULTANEOUSLY|YES|
|LLR03|IF USER INPUT IS PRESSED THRICE, ALL 4 LED SHOULD TURN ON IN CLOCKWISE MANNER (GREEN->ORANGE->RED->BLUE->GREEN)|YES|
|LLR04|IF USER INPUT IS PRESSED FOUR TIMES, ALL 4 LED SHOULD TURN ON IN ANTI-CLOCKWISE MANNER (GREEN->BLUE->RED->ORANGE->GREEN)|YES|
