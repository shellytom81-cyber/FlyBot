# FlyBot

A budget, smartphone-controlled micro-drone prototype powered by an ESP32 microcontroller, designed for lightweight agility and experimental edge-robotics[cite: 1].

## 🛠️ Hardware Bill of Materials (Under $50)
* **Microcontroller:** ESP32 (Seeed Studio XIAO ESP32-S3 or standard ESP32 module)[cite: 1]
* **IMU Sensor:** MPU-6050 6-axis gyroscope and accelerometer[cite: 1]
* **Actuators:** 4 x Coreless DC motors (716 or 8520 size)[cite: 1]
* **Motor Drivers:** 4 x MOSFETs (AO3401A or SI2302DS)[cite: 1]
* **Power Source:** 3.7V LiPo Battery (200mAh - 500mAh high discharge)[cite: 1]
* **Frame:** Custom 3D-printed ultra-lightweight micro X-frame[cite: 1]

## 🧠 Software Architecture
* **Flight Firmware:** Written in Arduino IDE using ESP32 libraries.
* **Stabilization:** Continuous PID feedback loop processing gyroscope data from the MPU-6050 to dynamically adjust motor speeds[cite: 1].
* **Control Interface:** Local Wi-Fi Access Point hosted directly on the ESP32, allowing control via a smartphone web browser or companion app[cite: 1].

## 🚀 Getting Started
1. Clone the repository: `git clone https://github.com/YOUR-USERNAME/flybot-micro-drone.git`
2. Open the `firmware/flight_controller/flight_controller.ino` file in the Arduino IDE.
3. Install required ESP32 and MPU-6050 sensor libraries.
4. Flash the code to your ESP32 board and connect to the drone's local Wi-Fi network from your mobile phone.
