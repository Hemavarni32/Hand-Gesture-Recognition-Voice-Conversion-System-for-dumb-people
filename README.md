# Hand Gesture Recognition and Voice Conversion System

## 📌 Project Overview
This project is a hardware-based communication system designed to assist speech-impaired individuals in expressing their basic needs using hand gestures.

The system uses IR (Infrared) sensors to detect hand movements. The detected gesture is processed by a Raspberry Pi, which converts predefined commands into voice output through a speaker.

---

## 🎯 Problem Statement
Speech-impaired individuals often face difficulties communicating their needs in hospitals, public places, and emergency situations where others may not understand sign language.

This project provides a simple, affordable, and effective gesture-based voice communication solution.

---

## 💡 Proposed Solution
Three IR sensors are placed to detect specific hand gestures:

- Left Sensor → "I need water"
- Middle Sensor → "I want to go to restroom"
- Right Sensor → "I need change of glucose strips"

When a gesture is detected:
1. The IR sensor sends a signal to Raspberry Pi.
2. The Python program reads the GPIO input.
3. A predefined voice message is generated.
4. The message is played through the speaker.

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
2. The sensor detects the obstruction.
3. Raspberry Pi processes the input signal.
4. The corresponding voice output is triggered.

---

## 📂 Project Structure
- README.md – Project explanation
- components_list.txt – Hardware component list
- Documentation folder – Contains project report and presentation
- Demo folder – Working model video

---

## 📽 Demo
The working model demonstration video is included in this repository.

---

## 🧠 Applications
- Hospitals
- Public service centers
- Home assistance for speech-impaired individuals
- Emergency communication systems

---

## 🔮 Future Improvements
- Camera-based gesture recognition
- Machine learning integration
- Wireless communication support
- Mobile application integration

---

## 📝 Implementation Note
The system was developed using Python on Raspberry Pi OS for IR sensor-based gesture detection and voice output generation.

The original source code file is not included in this repository.
The previous implementation is currently not in working condition.

