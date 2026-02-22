# Hand Gesture Recognition and Voice Conversion System

## 📌 Project Overview
This project is a hardware-based communication system designed to help speech-impaired individuals convey their basic needs using hand gestures.

The system uses IR (Infrared) sensors to detect hand movements. The detected gesture is processed by a Raspberry Pi, which then converts the predefined command into voice output using a speaker.

---

## 🎯 Problem Statement
Speech-impaired individuals often face difficulty communicating their needs, especially in hospitals, emergency situations, and public places where others may not understand sign language.

This project provides a simple and cost-effective solution for gesture-based voice communication.

---

## 💡 Proposed Solution
IR sensors are placed in strategic positions to detect hand gestures:

- Left Sensor  → "I need water"
- Middle Sensor → "I want to go to restroom"
- Right Sensor → "I need change of glucose strips"

When a gesture is detected, the Raspberry Pi processes the signal and triggers the corresponding voice output.

---

## 🛠 Hardware Components Used
- Raspberry Pi (Model 3 / 4)
- IR Sensors (3 units)
- Speaker / Audio Output
- Breadboard
- Jumper Wires
- 5V Power Adapter
- MicroSD Card (Raspberry Pi OS)

---

## 💻 Software Used
- Raspberry Pi OS (Linux)
- Python Programming Language
- RPi.GPIO Library
- Text-to-Speech Engine (espeak)

---

## ⚙️ Working Methodology
1. The user places their hand in front of a specific IR sensor.
2. The sensor detects the obstruction and sends a signal to Raspberry Pi.
3. Python program running on Raspberry Pi reads the GPIO input.
4. Based on the detected sensor, a predefined voice message is generated.
5. The message is played through the speaker.

---

## 📂 Project Structure
- README.md – Project explanation
- Documentation folder – Contains project report and presentation
- Demo folder – Contains working model video
- components_list.txt – List of hardware components

---

## 📽 Demo
The working model demonstration video is included in the repository.

---

## 🧠 Applications
- Hospitals
- Public service centers
- Homes for speech-impaired individuals
- Emergency communication systems

---

## 🔮 Future Improvements
- Add camera-based gesture recognition
- Implement machine learning for dynamic gesture detection
- Mobile application integration
- Wireless communication support

---

## 📝 Implementation Note
The system was developed using Python on Raspberry Pi OS for IR sensor-based gesture detection and voice output generation.

The original source code file is currently not included in this repository.

---

## 👩‍💻 Team Members
- Your Name
- Team Member Names