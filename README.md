# Motion_Detection_Using_PIR

🚪 **PIR-Based Automatic Door System using ESP32 (Wokwi Simulation)**

This project demonstrates an automatic door control system using an ESP32, a PIR motion sensor, a servo motor, and a buzzer.

The ESP32 board used in this project is manufactured by Espressif Systems, and the complete circuit and program were tested using the online simulator Wokwi.

📌 **Project Description**

In this project, a PIR motion sensor is used to detect human movement.

When motion is detected:

The servo motor rotates and opens the door.

The buzzer turns ON as an alert.

A message is printed on the Serial Monitor.

When no motion is detected:

The servo motor returns to its initial position and closes the door.

The buzzer turns OFF.

A status message is printed on the Serial Monitor.

This project is useful for understanding basic automation and security concepts using ESP32.

**🎯 Features**

Motion detection using PIR sensor

Automatic door opening using servo motor

Audio alert using buzzer

Serial monitor status messages

Fully simulated in Wokwi

**🔌 Pin Connections**
Component	ESP32 GPIO Pin
Servo signal pin	GPIO 21
Buzzer	GPIO 14
PIR sensor output	GPIO 12

**🔧 Power Connections**

PIR sensor:

VCC → 5V

GND → GND

Servo motor:

VCC → 5V

GND → GND

Buzzer:

One pin → GPIO 14

Other pin → GND

All grounds (GND) must be connected together.

**🧠 Working Principle**
The ESP32 continuously reads the output of the PIR motion sensor.

If the sensor output becomes HIGH:

The buzzer is activated.

The servo motor rotates to 90 degrees (door open).

A message is printed indicating that motion is detected.

If the sensor output is LOW:

The buzzer is turned OFF.

The servo motor moves back to 0 degrees (door closed).

A message is printed indicating that no motion is detected.

**🖥 Serial Monitor Output**

The following messages are displayed during execution:

Motion is detected --> The door is open!!

No Motion detected --> The door is closed!!

These messages help in monitoring the system behavior during simulation.

**🧪 Simulation Platform**

The complete circuit and code are simulated using the Wokwi online simulator.
This allows testing of the ESP32, PIR sensor, servo motor, and buzzer without physical hardware.

**🛠 Components Used**

ESP32 development board

PIR motion sensor

Servo motor

Buzzer

Jumper wires

Wokwi simulator

**📘 Learning Outcome**

This project helps beginners understand:

Digital input reading from a sensor

Controlling actuators such as a servo motor and buzzer

Basic automation logic using ESP32

Serial communication for debugging and monitoring

**✅ Application**

This system can be used as a basic model for:

Automatic door systems

Motion-based security alerts

Smart home entry control projects


**Author**: 
Amrutha D N
