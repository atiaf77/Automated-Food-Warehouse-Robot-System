# Automated Warehouse Robot Project

## Overview
This project aims to transform a food storage warehouse into a fully automated facility with minimal human intervention. The system utilizes autonomous mobile robots (AMRs) for handling, transporting, and organizing goods efficiently.

---

## Execution Algorithm
1. **Initialize System**  
   - Activate sensors, navigation, and communication modules.
2. **Mapping the Warehouse**  
   - Robots perform SLAM (Simultaneous Localization and Mapping) to generate a live warehouse map.
3. **Task Assignment**  
   - Warehouse Management System (WMS) assigns tasks to available robots based on proximity and battery level.
4. **Navigation & Obstacle Avoidance**  
   - Robots use LiDAR and cameras to detect paths and avoid obstacles in real time.
5. **Goods Handling**  
   - Robotic arms or conveyors load/unload items.
6. **Delivery & Storage**  
   - Items are delivered to designated zones with automated shelving.
7. **Battery Management**  
   - Robots autonomously navigate to charging stations when battery is low.
8. **Continuous Monitoring**  
   - Sensors track warehouse environment (temperature, humidity, safety).

---

## Robot Design
**Main Components:**
- **Base:** Mobile platform with omnidirectional wheels.
- **Sensors:** LiDAR, ultrasonic sensors, cameras for navigation.
- **Manipulator Arm:** 5-DOF arm for picking/placing items.
- **Power System:** Rechargeable lithium-ion battery pack.
- **Controller:** Industrial-grade microcontroller or single-board computer (e.g., Raspberry Pi, NVIDIA Jetson).
- **Communication:** Wi-Fi & IoT cloud integration.

---

## Working Envelope
The **working envelope** defines the physical space within which the robot can operate effectively.

**Elements of Working Envelope:**
1. **Reach Radius:** Maximum distance the arm can extend (e.g., 1.2m from center).
2. **Vertical Reach:** Maximum height (e.g., 2.5m).
3. **Mobility Area:** Entire mapped warehouse floor space.
4. **Load Capacity:** Max weight handled (e.g., 15 kg).
5. **Rotation Angle:** Arm rotation range (e.g., 360° base rotation).
6. **Safety Margin:** Buffer zones to prevent collisions.

---

## Diagram
![Warehouse Robot Diagram](diagram.png)

---

## License
This project is released under the MIT License.
