# ⚡ Smart Energy Harvesting Using Piezoelectric Sensor

A sustainable system designed to harvest mechanical energy from vibrations or pressure using piezoelectric sensors, converting it into usable electrical energy for powering low-power devices in remote or inaccessible environments.

---

## 🌟 Overview

This project showcases a **Smart Energy Harvesting System** that utilizes a piezoelectric sensor to convert mechanical stress (like footsteps or vibrations) into electrical energy. The generated energy is boosted, rectified, and regulated to charge a battery or directly power small electronic devices. The goal is to provide an eco-friendly energy source for IoT devices, wearables, and wireless sensors, especially in places lacking direct power access.

---

## 🎯 Objectives

- Capture mechanical energy using piezoelectric effect.
- Boost and convert the low AC voltage into usable DC voltage.
- Store the regulated voltage in a battery.
- Power low-energy applications sustainably.
- Analyze efficiency and real-world use cases.

---

## 🧱 Block Diagram

![Smart Energy Harvesting Block Diagram](https://github.com/user-attachments/assets/ef2d6608-d1ea-4d91-a88b-883180663c6d)

## 📐 Circuit Diagram and Description

![Smart Energy Harvesting Circuit Diagram](https://github.com/user-attachments/assets/86fd7a6c-14ad-459d-9228-74494133c04d)

🔹 Components:

- Piezoelectric Sensor – Generates voltage from vibration/pressure.
- Voltage Multiplier – Boosts low AC voltage using IN4148 diodes and 220µF capacitors.
- Bridge Rectifier – Converts AC to DC.
- Voltage Regulator (7805) – Outputs stable 5V DC.
- Battery Storage – Stores harvested energy (Li-ion or NiMH battery).
- Capacitors – Smooth voltage (100µF/220µF).
- Breadboard & Wires – Prototyping.

( Refer Datasheets attached at the end of report )

## 🔧 Working Principle

- Mechanical force on the piezoelectric sensor generates AC voltage.
- The voltage is boosted using a Cockcroft-Walton voltage multiplier.
- A bridge rectifier converts the boosted AC to DC.
- The DC is smoothed using capacitors and regulated to 5V using a 7805 IC.
- Energy is stored in a battery and can power small devices (like LEDs, sensors).

## 📊 Results

- Voltage Output: 2V–5V based on force applied.
- Power Generated: Up to 20 mW under strong pressure.
- Energy Storage: Can power a small LED for ~20 seconds after 30 minutes of force.
- Efficiency: Sufficient for intermittent low-power loads.

## 📌 Applications
 
- 👕 Wearable Electronics
- 🌿 Self-powered IoT Sensors
- 🛣️ Energy Harvesting from Footsteps on Roads
- 🏙️ Smart Building Monitoring
- 🚆 Railway or Bridge Structural Health Sensors

## 🧪 Limitations

- Low power output – only supports micro-energy applications.
- Relies entirely on mechanical vibrations.
- Voltage is inconsistent and depends on input force.
- Energy conversion and storage is not highly efficient.

## 🔮 Future Enhancements

- Use of advanced piezoelectric materials for higher efficiency.
- Integration of hybrid systems (solar, thermal, RF).
- More efficient power management ICs.
- Miniaturization for wearable and embedded devices.
- Improved storage systems (supercapacitors or advanced batteries).

## 📄 Documentation

- 📘 [Full Report](https://github.com/DuttPanchal04/Smart-Energy-Harvesting/blob/main/Smart%20Energy%20Harvesting%20Report.pdf)
- 📘 [Full Presentation](https://github.com/DuttPanchal04/Smart-Energy-Harvesting/blob/main/Smart-Energy-Harvesting%20Presentation.pptx)

## 🤝 Team & Acknowledgements

- 👨‍💻 Dutt Panchal
- 👨‍💻 Ved Patel
- 👨‍💻 Nayan Parekh

## ⭐ Follow & Connect

For more such sustainable tech and embedded projects,

🔗 [GitHub](https://github.com/DuttPanchal04)
🔗 [LinkedIn](https://www.linkedin.com/in/dattpanchal04/)
📧 Email: dattpanchal2904@gmail.com
