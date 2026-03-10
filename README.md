# STORED-GRAIN-PROTECTION-AND-SPOILAGE-ALERT-SYSTEM  🌾🔒

---DESCRIPTION---

The project is an IoT-based Stored Grain Protection and Spoilage Alert System using ESP32 and DHT22 sensor to track temperature and humidity.The system send real time data to the Blynk  mobile App and alerts users when conditions exceed safe limits to prevent grain spoilage.

---OBJECTIVE---

This project presents an IoT-based grain monitoring and spoilage alert system designed to protect stored grains from environmental conditions such as temperature and humidity changes. Improper storage conditions can lead to fungal growth, insect infestation, and grain spoilage, resulting in significant losses for farmers and warehouse managers.

The system uses an ESP32 microcontroller connected with a DHT22 temperature and humidity sensor to continuously monitor storage conditions. The collected data is transmitted to the Blynk IoT platform, allowing users to monitor the grain storage environment in real time using a mobile application.

If the temperature or humidity exceeds the predefined safe threshold values, the system immediately triggers a local alert using a buzzer/LED and sends a real-time notification to the user's smartphone through the Blynk app. This enables quick action to prevent grain damage.

The system is designed to be low-cost, energy-efficient, and easy to deploy, and it can be powered using solar energy, making it suitable for rural and agricultural environments.

# Key Features ✨

Real-time monitoring of grain storage conditions.
​
Automatic alerts via buzzer, LED, and Blynk app for unsafe temperature/humidity.
​
Solar-powered for eco-friendly, continuous operation.
​
Low-cost, simple setup compared to complex existing systems.
​
🚨 Auto alerts on spoilage risk

💰 Budget-friendly components

🔄 Non-stop 24/7 monitoring

# How It Works ⚙️

ESP32 reads data from DHT22 sensor, compares with thresholds, triggers local alerts if unsafe, and sends notifications via Blynk cloud. The system runs in a loop: collect data, process, alert if needed, and repeat.
​
📡 Sensor data → ESP32 processing

⚠️ Unsafe? Buzzer + app alert

🔄 Loop repeats continuously

# Components 🛠️

ESP32: IoT microcontroller with Wi-Fi for cloud connectivity.

​DHT22: Accurate temperature and humidity sensor.
​
Buzzer/LED: Local alerts.
​
Blynk App: Mobile dashboard for remote monitoring.
​
    📶 ESP32 (Wi-Fi IoT brain)

   🌡 DHT22 (temp/humidity sensor)

   🔔 Buzzer/LED (local alarms)

   📲 Blynk (app control)

# Advantages ✅

   🛡️ Stops spoilage & losses

   🌿 Solar energy efficient

   📈 Easy to scale up

# Setup Instructions 🚀

   Clone this repo: git clone [your-repo-url].

   Install dependencies: Arduino IDE with ESP32 board, Blynk library.

   Upload code to ESP32 (code in /src folder).
   
   Set up Blynk app with auth token.

   Power via solar panel and place sensors in grain storage.
​
   🗂️ Clone repo

   ⚙️ Install libs & flash code

   📲 Config Blynk

   ☀️ Deploy with solar
