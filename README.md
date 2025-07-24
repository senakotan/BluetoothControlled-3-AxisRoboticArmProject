#  Bluetooth-Controlled 3-Axis Robotic Arm

A **Bluetooth-enabled robotic arm system** controlled via an Android phone.  
This 3-axis arm can pick and place objects wirelessly with precision, making it ideal for **educational** and **embedded systems** applications.

## 🎯 Project Objective

To remotely control the robotic arm using an **Android device via Bluetooth**, allowing the arm to **move in 3 axes** and perform **object manipulation**.  
This demonstrates the integration of **electronic systems** with **wireless control technologies**.

## 🔩 Robot Arm Features

- **3-axis movement**: up/down, left/right, and rotation  
- **Capable of gripping and lifting** small objects  
- Executes **precise movements** via PWM-controlled servos  
- Designed for **versatile applications** in different tasks  
- Controlled wirelessly through a **custom Android app**

## 🔧 Components Used

- Android Phone  
- STM32F407 Microcontroller  
- HC-06 Bluetooth Module  
- 4x SG90 Servo Motors  
- 2x 3.7V Li-Po Batteries  
- Female-to-Male Jumper Wires  

## ⚙️ Component Specifications

- **SG90 Servos**: 4.8V–6V input, 0–180° rotation  
- **HC-06**: Bluetooth serial communication via UART  
- **STM32F407**: Generates PWM signals and processes UART commands  
- **Power Supply**: Portable design with 3.7V Li-Po batteries  

## 📱 Control Mechanism

A **custom Android application** sends **directional commands** over Bluetooth.  
Each button in the app corresponds to a **servo function** (e.g., rotate, lift, grip), allowing **real-time movement control**.

📄 You can also [view the project poster here](3EksenliRobotKol.jpg).


| Developed with STM32 💡 Passion for Embedded Systems & Robotics 🤖



---

