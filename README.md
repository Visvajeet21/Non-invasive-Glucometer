# Non-Invasive Glucometer

A non-invasive glucometer designed to measure blood glucose levels without the need for finger pricks or blood samples. This device utilizes infrared (IR) spectroscopy to determine glucose levels by analyzing light absorption properties of the skin. 

# Overview
The goal of this project is to create a non-invasive device for glucose monitoring that improves comfort and accessibility for patients with diabetes. Traditional glucometers require blood samples, which can be painful and lead to user discomfort over time. This project addresses these challenges using non-invasive optical technology.

# How It Works
The device utilizes an infrared light source that emits a specific wavelength known to interact with glucose molecules. The light reflects off or passes through the skin and is captured by a sensor. The reflected light is then analyzed, and based on absorption characteristics, glucose concentration is estimated using a predictive model.

# Features

1. Non-Invasive : Measures glucose levels without any need for blood samples.
2. Portable Design : Compact and lightweight, suitable for personal daily use.
3. Real-Time Monitoring : Provides immediate glucose level readings.
4. Data Storage : Logs glucose readings for future analysis and tracking.

# Technologies

# Hardware : 
  - Near-Infrared (NIR) LED (850 nm)
  - Photo Diode Sensor
  - Microcontroller (e.g., Arduino, ESP32)
  - Resistors, IC's, Capacitors, Potentiometer, LCD Display, Jumper Cables
  - 
# Software :
  - Regression Model (for glucose level estimation)
  - Arduino code for data analysis and preprocessing

# Hardware Setup

1. Sensor Assembly : Connect the NIR LED and photo diode sensor to the microcontroller. Follow wiring diagrams to ensure proper sensor placement and secure connections.
2. Microcontroller Programming : Install the Arduino IDE and upload the provided firmware to your microcontroller.
3. Power Supply : Use a power source compatible with the microcontroller. A rechargeable battery is recommended for portability.

# Usage
1. Turn on the Device: Power up the device and wait for the NIR sensor to initialize.
2. Calibration: If this is your first use, calibrate the device by following the setup steps in the application.
3. Measurement: Place the device on the skin (e.g., fingertip, palm) and initiate a reading. The LED will emit light, and glucose levels will be estimated based on the reflected light captured by the sensor.

# Data Viewing:
On LCD Display: Check readings directly on the LCD display.

# Algorithm and Analysis

1. Spectral Analysis: The reflected NIR light intensity at specific wavelengths is used to estimate glucose concentration based on known light absorption properties of glucose.
2. Machine Learning Regression Model: The device uses a trained machine learning model to map reflected light intensity to blood glucose levels. Training data was collected with labeled glucose concentrations and processed with algorithms to ensure accurate and reliable predictions.
3. Signal Processing: Preprocessing steps include noise filtering, normalization, and baseline correction to reduce errors and improve accuracy.

# Challenges and Future Work
1. Accuracy Improvement: Fine-tuning the algorithm for more precise results.
2. Calibration: Developing a universal calibration method for all users.
3. Battery Life Optimization: Exploring lower power components to increase battery life.
4. FDA Approval: Pursuing clinical testing and regulatory approval to ensure device safety and accuracy.
5. Bluetooth Connectivity: Syncs with mobile apps for data tracking and monitoring trends.

# Flowchart of working
![Screenshot_20221219_082540](https://github.com/user-attachments/assets/336d3856-99bc-4f39-8f3c-bada7daf68e9)

# Circuit Diagram
![Screenshot_20221222_111254](https://github.com/user-attachments/assets/d4242fe0-948c-41ef-93ae-78314b47f755)

# Result
![image](https://github.com/user-attachments/assets/0380b399-a9e9-4f7e-b530-bec173cc3b37)




   
