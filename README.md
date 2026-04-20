Accident Prevention Spectacles

A wearable smart safety system designed to prevent road accidents by monitoring driver behavior and environmental conditions using multi-sensor integration.

Features
Drowsiness detection using IR sensors
Head movement tracking using MPU6050 sensor
Real-time alerts (audio/vibration)
Automatic vehicle deceleration in case of driver unresponsiveness

System Overview
The system uses a multi-stage safety mechanism:

Detect driver fatigue/distraction
Trigger alert
Check response
If no response → initiate vehicle slowdown

Tech Stack
ESP32 / Arduino
Sensors: IR sensor, MPU6050
Communication: ESP-NOW
