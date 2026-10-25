# car-parking-system
code.ino — Arduino source code. * circuit_diagram.png — circuit connections. * project_photos/ — photos of your completed project. * components.md — components and their purposes.
https://wokwi.com/projects/478059040424627201

Note: This is a basic demonstration program. It assumes active-LOW IR sensor modules and uses a single ultrasonic measurement to confirm entry. For a reliable working model, sensor placement and gate timing must be tested. The slot count is stored only in memory, so it resets when the Arduino restarts. This version also does not verify that every entry corresponds to a completed exit.

 Working Principle

1. The ultrasonic sensor measures the distance to a vehicle near the entrance.
2. The entry IR sensor detects the vehicle.
3. If a parking slot is available, the Arduino updates the count and opens the gate.
4. The servo motor closes the gate after a short delay.
5. The exit IR sensor detects a vehicle leaving and updates the available-slot count.
6. The LCD displays the number of available slots.
7. Intelligent Smart Car Parking Management System Using Arduino UNO

Project Overview

The Intelligent Smart Car Parking Management System is an embedded systems project developed using Arduino UNO. It automates parking gate control and displays the estimated number of available parking slots.

Components Used

* Arduino UNO
* HC-SR04 Ultrasonic Sensor
* IR Sensor Modules
* SG90 Servo Motor
* 16×2 LCD Display
* 10 kΩ Potentiometer
* Breadboard and Jumper Wires

Features

* Automatic vehicle detection
* Servo-controlled parking barrier
* LCD-based parking status display
* Basic vehicle entry and exit tracking
* Embedded C/C++ programming

Technologies

* Arduino UNO
* Embedded C/C++
* Sensor Interfacing
* Microcontroller Programming

Applications

* Small parking facilities
* College parking demonstrations
* Residential parking prototypes
* Embedded systems learning projects

Future Improvements

* Individual parking-slot sensors
* Accurate vehicle entry/exit verification
* EEPROM-based slot-count storage
* IoT-based parking availability monitoring
* Mobile application integration

Author

Gunasealan K.

Project Type

Embedded Systems / Internet of Things (IoT)
