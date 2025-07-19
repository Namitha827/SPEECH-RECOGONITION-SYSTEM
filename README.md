# SPEECH-RECOGONITION-SYSTEM

*COMPANY*: CODETECH IT SOLUTIONS

*NAME*: NAMITHA.J.B

*INTERN ID*: CT04DZ84

*DOMAIN*: EMBEDDED SYSTEMS 

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTHOSH


**This project is a simulation of a speech recognition-based control system using Arduino Uno, aimed at controlling a light bulb through voice-like commands. It is developed as part of the CODTECH Internship Task-4. Since Tinkercad does not directly support real-time audio or speech input, the system simulates voice command functionality using Serial Monitor input, which represents the output of a voice recognition module or mobile voice assistant.

The primary objective of this system is to create a basic automation setup where a user can turn a light bulb ON or OFF through simulated voice commands. In a real-world scenario, this would involve using a Bluetooth module (HC-05) or a voice recognition module (like Elechouse V3) to process speech and convert it into digital control commands. However, in this simulation, the speech commands are manually input via the Serial Monitor, using the characters '1' and '0' to represent "Turn ON" and "Turn OFF" commands respectively.

The hardware components used include:

Arduino Uno

Light bulb module (or lamp)

Relay module (to control high-voltage devices like bulbs)

Breadboard

Jumper wires

Serial Monitor (in place of a voice input system)


The light bulb cannot be directly powered by Arduino pins due to current limitations. Instead, a relay module is used as a switch. The Arduino sends a LOW/HIGH signal to the relay’s control pin to open or close the connection between the light bulb and the power supply, mimicking how real electrical appliances are managed in smart homes.

In the Arduino sketch, serial communication is initialized using Serial.begin(9600);, and the relay control pin is set as output. The program continuously checks if a character has been received through the serial interface. If '1' is received, the relay is activated, and the light bulb turns ON. If '0' is received, the relay deactivates, turning the light OFF. This allows for simple simulation of voice-controlled lighting using typed commands.

To test the system:

1. Start the simulation in Tinkercad.

2. Open the Serial Monitor.

3. Type 1 and press Send → the light bulb turns ON.

4. Type 0 and press Send → the light bulb turns OFF.


This project replicates real-world applications such as smart home lighting, IoT-based control systems, and assistive technologies for the elderly or disabled, who can use voice commands instead of physical switches.

In conclusion, this speech-recognition-based light control system demonstrates how embedded systems can be programmed to respond to simple digital signals representing voice commands. While actual speech recognition hardware is not used in this simulation, it lays the groundwork for implementing more advanced smart home automation systems using Arduino and external voice recognition modules.


*OUTPUT*:

<img width="1366" height="501" alt="Image" src="https://github.com/user-attachments/assets/8d7ed691-4a7a-44d0-aa1b-db4d9617a4fd" />
