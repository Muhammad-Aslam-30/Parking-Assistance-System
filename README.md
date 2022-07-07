# Parking Assistance System

For this project, the plan is to use an Arduino with an ultrasonic sensor and a beeper to signal the distance to the objects by differing the beeper's tone frequencies. Below, is the circuit diagram for the project.

# Circuit diagram

<img width="416" alt="Circuit-diagram" src="https://user-images.githubusercontent.com/102525782/173813035-45c9a8c1-abc5-418f-9655-0d6244ad6ae5.png">

## Features
* The system activates as soon as it is supplied with power.   
* It is connected to a beeper which gets triggered in four different ways depending on the situation.
* Beeps with a delay of 100 milliseconds when the distance between the Ultrasonic sensor and the object is between 0-10 cm.
* Beeps with a delay of 500 milliseconds when the distance between the Ultrasonic sensor and the object is between 11-50 cm.  
* Beeps witha a delay of 1000 milliseconds when the distance between the Ultrasonic sensor and the object is between 50-100. 
* If the distance between the object and Ultrasonic sensor is above 100 cm, buzzer stops beeping.


## Hardware Used
S. No   | Hardware
------------- | -------------
1           | Arduino Uno board 
2         | USB cable for Arduino
3        | Ultrasonic sensor HC-SR04
4         | Beeper 780-0712 
5         | Breadboard
6         | 9V battery with connector
7         | Connecting wires


## Ultra sonic Sensor + Beeper connection
Arduino Pin   | Ultra sonic Sensor + Beeper connection
------------- | -------------
CYAN           | 5V or 3V   
BLUE         | GND (GROUND)
RED        | D4 (Digital Pin Four)
RED        | D5 (Digital Pin Five)
WHITE        | D6 (Digital Pin Six)

![ultr](https://user-images.githubusercontent.com/102525782/177778061-f6af4295-fb47-4cef-bc99-31b18fd6f912.jpg)
![ard_d](https://user-images.githubusercontent.com/102525782/177778072-bb642163-3e89-4187-acd6-5cf8e56e19a2.jpg)
![ard_p](https://user-images.githubusercontent.com/102525782/177778078-6f9e4f13-a746-4270-be3d-1a65b6a61c62.jpg)
![buzzer](https://user-images.githubusercontent.com/102525782/177778084-b6b2d0fd-3f58-426e-97d6-3eed141df7fe.jpg)
