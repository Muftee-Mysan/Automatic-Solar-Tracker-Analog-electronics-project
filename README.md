# Analog-electronics-project

# Automatic Solar Tracker

Welcome to the repository of the **Automatic Solar Tracker**, a project aimed at maximizing the efficiency of photovoltaic (PV) systems by maintaining optimal alignment between solar panels and the sun throughout the day. This innovative system combines analog control techniques and sustainable design principles, making it a cost-effective and eco-friendly solution for solar energy optimization.

---

## 🌟 Project Overview

Solar power is one of the most sustainable energy sources, especially in sun-rich regions. However, fixed solar panels often fail to capture maximum sunlight throughout the day due to the changing position of the sun. The **Automatic Solar Tracker** addresses this limitation by dynamically adjusting the orientation of solar panels using a single-axis tracking mechanism.

The system incorporates:

- **Light-dependent resistors (LDRs):** For detecting sunlight intensity.
- **PID controller:** Implemented using operational amplifiers for precise alignment.
- **Motor driver:** Ensures smooth panel movement.
- **Pulse-Width Modulation (PWM):** Controls the motor speed.

---

## ⚙️ Features

1. **Sunlight Sensing:** Measures light intensity using LDRs to detect the sun's position.
2. **PID Control:** Maintains precise alignment through Proportional-Integral-Derivative adjustments.
3. **Motor Control:** Adjusts panel orientation efficiently.
4. **Eco-Friendly Design:** The enclosure combines wood and 3D-printed PLA for sustainability and durability.
5. **Compact Design:** A two-layer PCB integrates all electronic components seamlessly.

---

## 📐 System Design

### Block Diagram

![block_diagram](https://github.com/user-attachments/assets/e5f288f8-3901-424d-bf05-749a752ea1ea)


The system architecture consists of sunlight sensors, a PID controller, motor control circuitry, and a robust enclosure.

### Circuitry

- **Error Signal Generation:** Processes the voltage difference between LDRs to determine misalignment.
- **PWM Generation:** Controls motor speed to correct panel orientation.
- **Motor Driver Circuit:** Drives the motors responsible for panel adjustments.

### Breadboard Implementation
![breadboard](https://github.com/user-attachments/assets/87787f1e-07e4-4d6c-b4c4-04740c24582d)


### Simulation and Testing

Multisim simulations validated the functionality of the PID controller and PWM generation. Real-world testing confirmed enhanced solar energy capture.
- Square wave and Triangular wave:
![square_simulation](https://github.com/user-attachments/assets/19989e0b-d9f7-420d-bd82-9f2da7dec5be)
- Rectified triangular wave:
![triangle_simulation](https://github.com/user-attachments/assets/afdabe41-1255-480c-a757-4b6a5441154b)
- PWM signal:
![PWM_simulation](https://github.com/user-attachments/assets/e9753e81-cea0-4660-93a0-3859b7b5abd8)



---

## 🖼️ Project Images

1. **System Prototype**
   ![final_product](https://github.com/user-attachments/assets/1e0297f5-0b4b-425c-8695-d4452fc2bd68)

2. **PCB Design**

- Schematic:  
![PCB Schematic](https://github.com/user-attachments/assets/b233b9ca-d73d-46f9-b074-293748796eea)
- 3D Layout:
![Screenshot 2024-12-17 223625](https://github.com/user-attachments/assets/f4833c39-6272-4f3d-905c-cbf0b604e507)
- Top Layer:
![Screenshot 2024-12-17 223343](https://github.com/user-attachments/assets/5330f9e0-922c-413b-a3ca-74064b104028)
- Bottom Layer:
![Screenshot 2024-12-17 223431](https://github.com/user-attachments/assets/789ed12f-f18b-4503-85fc-a29931baa3e0)


4. **Enclosure**

![wood assembly](https://github.com/user-attachments/assets/5a8ca8b4-f118-46fa-b1df-599e9ac69fa6)

---

## 📋 Specifications

- **Controller:** Analog PID using operational amplifiers.
- **Sensors:** Light-Dependent Resistors (LDRs).
- **Power Source:** Solar panel output.
- **Enclosure Materials:** Wood and PLA.

---

## 🔧 Assembly

The assembly involves integrating electronic components onto a compact PCB, crafting the enclosure, and configuring the system for dynamic solar tracking.
![final assembly](https://github.com/user-attachments/assets/efc6c952-43a4-444c-a74f-858255f2c839)


---

## 🚀 Future Improvements

1. Upgrade to a dual-axis tracking system for enhanced efficiency.
2. Transition from analog to digital control for better accuracy and flexibility.
3. Integration with IoT for remote monitoring and control.

---

## 🎥 Project Video
Watch our detailed walkthrough of the Automatic Solar Tracker in action: https://youtu.be/nHiQHz7_xqY?si=oewumcQw3HjwGN45 

## 🤝 Acknowledgments

We thank the Department of Electronic & Telecommunication Engineering at the University of Moratuwa for providing the resources and guidance necessary for this project.

---


