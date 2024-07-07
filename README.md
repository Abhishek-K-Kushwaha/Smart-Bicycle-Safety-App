# Smart Bicycle Safety System - Parental Monitoring App

This project implements a smart bicycle safety system using Android devices to monitor a child's safety during cycling activities. The system leverages embedded hardware sensors (gyroscope, accelerometer, GPS, microphone, antenna) in conjunction with mobile devices to provide real-time monitoring and alerts to parents.

## Features

- **Real-time Monitoring:**
  - Continuously monitors GPS, accelerometer, and gyroscope data to detect:
    - Overspeeding
    - Fall detection (minimizing false positives)
    - Boundary crossing (geofencing)

- **Alerts and Notifications:**
  - Alerts on Phone A (child's device):
    - Beep alarm for overspeeding and fall detection.
    - Real-time location displayed on Phone B (parent's device) using an image of the local map.
    - Audible alerts on Phone B for overspeeding and fall detection.

- **Emergency Response:**
  - In case of a fall:
    - Alarm on Phone A with option to disable.
    - Real-time location sent to Phone B.
    - Automatic activation of microphone on Phone A if alarm isn't disabled within 5 seconds.
    - SOS transmission to Phone B with recorded sound via mobile internet.

## Demonstration
   - Watch the [demo video on YouTube](https://www.youtube.com/watch?v=AEmAife6-UQ&list=LL&index=6) showcasing the app's functionality.

