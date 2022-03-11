# Report
Remote keyless entry (RKE) and its features has multiplied automobile buyers/users and it is a very popular thing in modern markets. This report provides us an overview of RKE systems and tells us how they meet requirements such as range, battery life, reliability and regulatory compliance etc.

In one of the surveys conducted by BOSCH & other Automotive companies its seen that the installation rate for RKE systems in new vehicles is more than 80% in North America and more than 70% in Europe.
## Uses(Advantages):
* RKE-actuated vehicle-immobilization technology minimizes car theft.
* RKE vehicles offer the status of the car smartly.

## Working

An RKE system consists of an RF transmitter in the keyfob (or key) that delivers a short burst of digital data to a receiver in the car, which decodes it and uses receiver-controlled actuators to open or close the vehicle doors or trunk. In the United States and Japan, the wireless carrier frequency is 315MHz, whereas in Europe, it is 433.92MHz (ISM band). Frequency-shift keying (FSK) is utilised in Japan, but amplitude-shift keying (ASK) is used in most other regions of the world. The carrier oscillates between two levels of amplitude modulation: The lower level is frequently near zero to save power, resulting in complete on-off keying (OOK).

![RKE Bidrectional](https://user-images.githubusercontent.com/98825618/157854596-a64c06a9-5126-40ab-a5ae-c34883333c40.PNG)

Typical RKE systems (Figure) include a microcontroller in the key. The car is unlocked by pressing a pushbutton on the key, which wakes up the microcontroller. The microcontroller sends a stream of 64 or 128 bits to the key's RF transmitter, which modulates the carrier and transmits it via a simple printed-circuit loop antenna. The same signal is sent back givin the information like Window status, Door status, Alarm status, Car battery info etc. making it a very handy tool and technique for maintainence.

The following functionalities invoked by this preocedure is as follows:
* Window status Function - When the switch is pressed 1 time, then the all the LEDs present there should get on.
* Alarm status Function - When the switch is pressed 2 times, then the all the LEDs present there should get off.
* Car Battery information Function - When the switch is pressed 3 times, then all the LEDs should get on in clockwise direction.
* Door status Function - When the switch is pressed 4 times, then all the LEDs should get on in anticlockwise direction.

