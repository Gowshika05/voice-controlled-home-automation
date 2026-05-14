# voice-controlled-home-automation
IoT based voice controlled home automation system using NodeMCU ESP8266 and Amazon Alexa

# Voice Controlled Home Automation System using Amazon Alexa

#Overview
This project is an IoT-based home automation system that allows users to control household appliances using voice commands through Amazon Alexa. The system is developed using NodeMCU ESP8266 and Arduino IDE to enable wireless communication and smart appliance control. The project demonstrates the implementation of voice-enabled automation for improving convenience, energy efficiency, and smart home integration.

# Features
- Voice control using Amazon Alexa
- Wireless appliance control using Wi-Fi
- Real-time ON/OFF switching
- Smart home automation using IoT
- User-friendly and efficient system
- Low-cost implementation using ESP8266

#Technologies Used
- Arduino IDE
- NodeMCU ESP8266
- Amazon Alexa
- Embedded Systems
- Internet of Things (IoT)
- Wi-Fi Communication

#Components Required
- NodeMCU ESP8266
- Relay Module
- Breadboard
- Jumper Wires
- Power Supply
- Bulb 
- Amazon Alexa App

# Working Principle
  -The Voice Controlled Home Automation System is designed to automate and control household electrical appliances using voice commands through Amazon Alexa. The system combines Internet of Things (IoT) technology, wireless communication, and embedded systems to provide a smart and efficient home automation solution.

  -The core component of the system is the NodeMCU ESP8266 microcontroller, which contains an inbuilt Wi-Fi module for internet connectivity. The NodeMCU acts as the central controller of the entire system and is programmed using Arduino IDE.

  -Initially, the NodeMCU connects to the local Wi-Fi network using configured SSID and password credentials. Once connected to the internet, it establishes communication with Amazon Alexa through cloud-based IoT services.

  -A 5V relay module is connected to the GPIO pins of the NodeMCU. The relay acts as an electrically operated switch that controls the power supply to appliances such as bulbs and DC motors. Since the NodeMCU operates at low voltage, the relay module safely interfaces low-power control signals with high-voltage appliances.

  -When the user gives a voice command such as: “Alexa, turn on the light” the command is captured and processed by Amazon Alexa using speech recognition and cloud services. Alexa then sends the command through the internet to the NodeMCU ESP8266.

  -The NodeMCU continuously monitors incoming commands from the cloud platform. After receiving the command, the controller identifies the target appliance and generates the appropriate GPIO control signal.

  -The GPIO signal activates the corresponding relay channel, causing the relay contacts to switch state. As a result, the connected appliance turns ON or OFF based on the user command.

  -The entire process occurs within a few seconds, enabling real-time wireless control of appliances from anywhere with internet access.

  -The system can also control multiple appliances independently by connecting additional relay channels to different GPIO pins of the NodeMCU.

This project demonstrates:
- IoT-based smart home automation
- Voice-controlled embedded systems
- Wireless communication using Wi-Fi
- Real-time appliance switching
- Cloud-based automation control
The system improves convenience, reduces manual effort, and provides an efficient low-cost smart home solution using modern IoT technologies.

