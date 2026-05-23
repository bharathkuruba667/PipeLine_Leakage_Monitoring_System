# 🚰 Pipeline Leakage Monitoring System

![ESP32](https://img.shields.io/badge/ESP32-Microcontroller-blue)

![IoT](https://img.shields.io/badge/IoT-Blynk-green)

![Arduino](https://img.shields.io/badge/Arduino-Embedded-orange)

![Sensors](https://img.shields.io/badge/Sensors-Flow%20Sensors-red)

![Status](https://img.shields.io/badge/Project-Completed-success)
 
An IoT-based smart monitoring system designed to detect water leakages in pipelines using real-time flow rate comparison between two points in the pipeline network.
 
---
 
# 📌 Project Overview
 
The **Pipeline Leakage Monitoring System** continuously monitors water flow using dual flow sensors placed at different locations in a pipeline. By comparing the inlet and outlet flow rates, the system can detect leakages when there is a significant difference in readings.
 
The project is built using an **ESP32 microcontroller** with both **Online (IoT)** and **Offline** monitoring capabilities, ensuring reliable operation even without internet access.
 
The system also includes:

- Real-time monitoring using the Blynk IoT dashboard

- Local alerts using LCD display, RGB LED, and buzzer

- Water pump control using L298N motor driver

- Manual leakage simulation using a valve mechanism
 
---
 
# 🚀 Features
 
- Real-time water leakage detection

- Dual flow sensor comparison system

- IoT monitoring using Blynk

- Online and Offline operating modes

- LCD-based live status display

- RGB LED leakage indication

- Buzzer alert system

- Water pump control using ESP32

- Leakage simulation using valve mechanism

- Low-cost and scalable solution
 
---
 
# 🎯 Problem Statement
 
Water leakages in pipelines lead to:

- Water wastage

- Financial losses

- Infrastructure damage

- Increased maintenance costs
 
This system aims to provide:
> A smart real-time pipeline leakage monitoring and alert system using IoT and embedded technology.
 
---
 
# ⚙️ System Components
 
## 🔹 Hardware Components
 
| Component | Description |

|------------|-------------|

| ESP32 | Main microcontroller for processing and IoT communication |

| Flow Sensors | Measure water flow at two pipeline points |

| L298N Motor Driver | Controls the water pump |

| Submersible Pump | Simulates water flow in pipeline |

| LCD Display | Displays system status and flow readings |

| RGB LED | Indicates leakage status visually |

| Buzzer | Provides audible leakage alerts |

| Rocker Switches | Controls system and pump power |

| Valve | Used to manually create leakage |
 
---
 
# 🔍 Working Principle
 
1. Water flows through the pipeline using the submersible pump.

2. Two flow sensors measure flow rates at different points.

3. ESP32 compares both readings continuously.

4. If the difference exceeds a predefined threshold:

   - Leakage is detected

   - Buzzer activates

   - RGB LED changes color

   - Alert is displayed on LCD

   - Data is updated on Blynk dashboard

5. System continues monitoring in real-time.
 
---
 
# 🌐 IoT Monitoring
 
The project uses the **Blynk IoT platform** for:

- Remote monitoring

- Live flow rate visualization

- Leakage alerts

- System status updates
 
---
 
# 📊 System Modes
 
## 🟢 Online Mode

- Connected to WiFi

- Sends real-time data to Blynk dashboard

- Enables remote monitoring
 
## 🔴 Offline Mode

- Works without internet

- Local alerts remain functional

- LCD and buzzer continue operation
 
---
 
# 🛠 Tech Stack
 
- **ESP32** – Main controller

- **Arduino IDE** – Programming environment

- **Embedded C/C++** – Firmware development

- **Blynk IoT** – Cloud monitoring platform

- **Flow Sensors** – Water flow measurement

- **L298N Driver** – Pump motor control
 
---
 
# 🔌 Circuit Functionalities
 
- ESP32 reads pulse outputs from both flow sensors

- Flow rate calculations performed in real-time

- L298N controls submersible pump

- RGB LED indicates:

  - Green → Normal flow

  - Red → Leakage detected

- Buzzer activates during leakage

- LCD displays:

  - Flow 1 value

  - Flow 2 value

  - Leakage status
 
---
 
# 📈 Applications
 
- Smart water distribution systems

- Industrial pipeline monitoring

- Agricultural irrigation systems

- Residential water management

- Smart city infrastructure
 
---
 
# 💡 Key Learnings
 
- Real-time sensor data processing

- ESP32 IoT integration

- Flow sensor calibration

- Embedded system debugging

- Online and offline system design

- IoT dashboard integration using Blynk
 
---
 
# 🔮 Future Enhancements
 
- GSM/SMS alert integration

- Mobile application support

- Cloud data logging

- AI-based leakage prediction

- Solar-powered operation

- Automatic valve shutdown system

- Multiple pipeline monitoring support
 
---
 
# ▶️ Setup Instructions
 
## 1️⃣ Clone the Repository
 
```bash

git clone https://github.com/yourusername/pipeline-leakage-monitoring-system.git

cd pipeline-leakage-monitoring-system
 
