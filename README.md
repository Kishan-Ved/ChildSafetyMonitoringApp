# ChildSafetyMonitoringApp
This project consists of a mobile application to monitor child safety while cycling using the phone's GPS sensor, accelerometer and orientation sensor. There is also a provision of a free real time call using the local network. This app was made as an assignment in the Signal Systems and Random Processes course at IITGN. This app is also integrated with a mini-version of Google Maps, made from scratch, for the IITGN campus, which allows real time location sharing.

## Problem Statement:
Design and deploy an Android/iOS app for a smart bicycle to help parents monitor their child’s safety.

The smart bicycle has embedded hardware sensors and systems such as a gyroscope, accelerometer, GPS, microphone, and antenna. For this problem statement, assume that your Android/iOS mobile phone (Phone A)  behaves as the smart IoT embedded system and you are riding a (sensorless old-fashioned) bicycle. It should be able to transmit the data to your partner's device (parents’ Android/iOS mobile hereafter referred to as Phone for warning.

The child-monitoring Android/iOS app (during cycling) should be able to do the following:

1. Continuously monitor the GPS, accelerometer, and gyroscope data of your phone to determine the following

Over speed
Fall detection
Boundary crossing (define some geographical coordinates on campus)
Note: Your device should detect actual falls and avoid false detection like bumps or braking.

2. If the cycle goes beyond a particular perimeter, or over speeds, your device should do the following:
Play a beep alarm sound on your device (Phone A).
Display the real-time location of phone A on phone B using Google Maps and play a beep sound on Phone B.
3. If the cycle falls, your device should do the following:
Play a beep alarm sound on your device (Phone A), with an option to switch OFF the alarm.
Display the real-time location of phone A on phone B using Google Maps and play a beep sound on Phone B.
If the alarm is not switched OFF within 5 seconds by Phone A, a) Switch on the microphone and camera of phone A automatically and start recording. b) Send an SOS from phone A to phone B by transmitting the recorded sound and images using mobile internet network. 

## Demonstration: Youtube video link

https://youtu.be/dTsebtbNd6s

## Tech used:

MATLAB (for the backend - converted to C)\

Simulink (for building the UI)

TCP IP Protocols (for real time data transfer)

## UI

Phone A:

![pic1](https://github.com/Kishan-Ved/ChildSafetyMonitoringApp/assets/124593234/811678f8-ed99-48b5-9266-f9b40c47f931)

Phone B:

![pic2](https://github.com/Kishan-Ved/ChildSafetyMonitoringApp/assets/124593234/fac1bc80-becc-4708-b032-4e9882c2be8e)
