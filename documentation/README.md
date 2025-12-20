This folder contains block diagram, system architectural design, TFluna distance calcultor flowchart, video stream algorithm flowchart and design documentation for the ESP32-CAM Surveillance Rover project.

# System Documentation

## Block Diagram
![Block Diagram](Block%20Diagram.jpeg)
**Figure 1:** Overall blockdiagram proposed for the system showing sensor calibration and data acquisition and how the data is processed leading to an obstacle detection and further movement execution based on it. 

## Systme Architectural Design
![System Archiectural Design]()
**Figure 2:** GPIO pin mapping between ESP32-CAM, L298N motor driver, and TF-Luna LiDAR sensor.

## Architecture Flowchart
![Architecture](architecture_flowchart.png)
**Figure 3:** Control flow describing video streaming, command handling, and motor actuation logic.

