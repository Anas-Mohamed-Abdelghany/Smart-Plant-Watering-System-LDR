# Smart-Plant-Watering-System-LDR

🌱 An automated plant watering system using Arduino, featuring dual sensing technology with soil moisture monitoring and LDR-based light detection enhanced by optical lenses.

## 📝 Description
This project implements an intelligent plant care system that automatically monitors soil moisture levels and ambient light conditions. The system uses a combination of soil moisture sensors and light-dependent resistors (LDR) with focusing lenses to provide optimal care for plants. When soil moisture falls below a set threshold, the system automatically activates a water pump to irrigate the plant.

## ✨ Features
- Real-time soil moisture monitoring
- LDR-based light detection with optical lens enhancement
- Automated water pump control
- LCD display for system status
- Energy-efficient operation
- Non-blocking code implementation

## 🛠️ Hardware Requirements
- Arduino UNO/Nano
- 16x2 LCD Display
- Soil Moisture Sensor
- Light Dependent Resistor (LDR)
- Relay Module
- Water Pump
- Focusing Lenses
- Jumper Wires
- Power Supply

## 📋 Pin Configuration
```
LCD Display:
- RS: Pin 12
- EN: Pin 11
- D4: Pin 4
- D3: Pin 3
- D2: Pin 2
- D1: Pin 1

Soil Moisture Sensor:
- Analog Pin: A1

Relay Module:
- Digital Pin: 7
```

## 📊 System Operation
- The system continuously monitors soil moisture levels
- When moisture falls below threshold (250), pump activates
- LCD displays real-time status of soil condition and pump
- LDR with lens system monitors ambient light conditions
- Serial monitoring available for debugging

## 🔧 Calibration
- Default soil moisture threshold: 250
- Adjust `soilThreshold` value based on your sensor and plant needs
- Update `interval` value (currently 2000ms) for different reading frequencies

## 👥 Contributors
- Ziad Osama
- Hassan Badawy
- Mostafa Hany
- Nada Mostafa

## 📸 Project Images

![IMG_6070](https://github.com/user-attachments/assets/671a4c9f-0cbd-45d4-8f54-9ac08c8b4253)

## 📝 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check [issues page](../../issues).

## 📫 Contact
https://github.com/Anas-Mohamed-Abdelghany
https://www.linkedin.com/in/anas-mohamed-716959313/
