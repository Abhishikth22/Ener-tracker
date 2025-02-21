# Ener-tracker
Calculating daily power consumption and generating a total bill each day
This project is a smart energy meter using an ESP32, Blynk, and an I2C LCD display. It monitors voltage, current, power consumption, and calculates electricity cost in real-time. The data is displayed on an LCD screen and sent to the Blynk app for remote monitoring. Additionally, it can send bill updates via Telegram.

🎯 Features
✅ Real-time Energy Monitoring – Measures voltage (V), current (A), and power (W)
✅ Cost Calculation – Calculates electricity cost based on usage
✅ Blynk App Integration – View live readings from anywhere
✅ I2C LCD Display – Shows energy stats on a screen
✅ EEPROM Storage – Saves energy data even after power loss
✅ Telegram Notifications – Sends energy bill updates via Telegram
✅ Reset Button – Clears stored energy usage

🛠️ Components Used
🔹 ESP32 – The brain of the project
🔹 SCT-013 / ACS712 Sensor – Measures current consumption
🔹 Voltage Sensor (ZMPT101B) – Measures voltage
🔹 LCD Display (I2C 16x2) – Shows real-time data
🔹 Wi-Fi Module – Enables cloud connectivity
🔹 EEPROM Memory – Stores usage data
🔹 Blynk & Telegram APIs – For remote monitoring & notifications

📡 How It Works
1️⃣ The ESP32 reads voltage and current from sensors
2️⃣ Calculates energy (kWh) and cost based on a predefined rate
3️⃣ Displays the values on the LCD screen
4️⃣ Sends data to the Blynk app every few seconds
5️⃣ Saves energy data in EEPROM to prevent data loss
6️⃣ Sends a bill summary via Telegram every minute
7️⃣ Allows users to reset energy stats using a button

