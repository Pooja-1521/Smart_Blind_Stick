# Smart Blind Walking Stick with Location Detection

Blind and visually impaired find difficulties in detecting obstacles while walking in the street. 
The system is intended will provide artificial vision and object detection, as well as  real-time assistance 
via making use of IoT. 
The main objective of our project is to provide IOT-based assistance to blind people.  
The issues related to this project which involves providing a smart electronic aid for blind people to provide artificial vision and 
object detection, real assistance via GPS module by using IOT. Our project mainly focuses 
on visually impaired people who cannot walk independently environment.The 
aim of the overall system is to provide a low-cost and efficient navigation and obstacle 
detection aid for the blind which gives a sense of artificial by providing 
information about the environmental scenario of static and dynamic objects around them, so 
that they can walk independently.

Features
- Obstacle Detection: Uses ultrasonic sensors to detect obstacles and alerts the user via buzzer and LED.
- Location Tracking: Sends real-time GPS coordinates to a mobile app.
- Emergency Alerts: Sends SMS alerts with location details.
- IoT Integration: Connects with the Blynk IoT app for remote tracking.

Hardware Components

Arduino Uno / ESP8266 | Microcontroller |
Ultrasonic Sensor (HC-SR04) | Detects obstacles |
Buzzer & LED| Provides alerts |
GPS Module (NEO-6M / SIM808) | Tracks location |
GSM Module (SIM900A / SIM800L)| Sends SMS alerts |
Battery (9V Li-ion) | Portable power |

Software Setup

1. Install Arduino IDE
- Download: [Arduino Software](https://www.arduino.cc/en/software)
- Install the following libraries:
  ```cpp
  #include <TinyGPS++.h>  
  #include <SoftwareSerial.h>
  ```
- Connect your Arduino board and select the correct COM port.

2. Install Blynk App
- Download Blynk from the Play Store/App Store.
- Create a new project and obtain the **Auth Token**.
- Add a GPS Widget and set Virtual Pin (V1) for location tracking.

3. Upload Code to Arduino
- Upload the obstacle detection and GPS tracking code to your board.
- Open the Serial Monitor (9600 baud rate) to check sensor readings.

project look:

[project look](https://github.com/user-attachments/assets/f4d60c4f-d0f6-4052-a23e-fa2388b310e6)



