# Parking Assistance System

For this project, the plan is to use an Arduino with an ultrasonic sensor and a beeper to signal the distance to the objects by differing the beeper's tone frequencies. Below, is the circuit diagram for the project.

# Circuit diagram

<img width="416" alt="Circuit-diagram" src="https://user-images.githubusercontent.com/102525782/173813035-45c9a8c1-abc5-418f-9655-0d6244ad6ae5.png">

# Hardware requirements

Arduino Uno board, USB cable for Arduino, Ultrasonic sensor HC-SR04, Beeper 780-0712, Breadboard, 1K ohm resistor, Transistor, 9V battery with connector, number of connecting wires - 10


# Embedded-Systems-Parking-Assistance-System-
## Parking Assistance System using <a href="http://arduino.cc/"> "Arduino"</a> 
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

![ard_p](https://user-images.githubusercontent.com/102525782/177777801-391e3d6f-c392-4de4-a867-fd28c0cce340.jpg)
![ultr](https://user-images.githubusercontent.com/102525782/177777788-195bb074-4a95-436f-9255)
![buzzer](https://user-images.githubusercontent.com/102525782/177777803-aee116f8-4ec1-4c1b-8680-63e03e4eaff1.jpg)
-66e8d3fe32f4.jpg)
![ard_d](https://user-images.githubusercontent.com/102525782/177777797-ba4336d7-425e-43a1-a4a9-7a59a26791eb.jpg)


## Variables to Note
Variable Name     | What it does
------------------| -------------
distance            | **Int** that holds the value of distance in centimeters.
duration               | **Long** 
