# 🚑 ResBot - Emergency Delivery Robot

**ResBot** is an **Arduino-powered, four-wheeled robot** designed for delivering **medical and emergency supplies** (e.g., food, water, medicine) in challenging environments such as **earthquakes, hurricanes, and rough terrains**. It features **WiFi control via a smartphone**, **obstacle detection**, and a **camera** for remote monitoring.

## 📸 Screenshots
![ResBot in Action](./assets/resbot-demo.png)

## 🚀 Features
- 🏎️ **Four-wheel drive** for stability and movement.
- 📷 **Camera integration** for live video feed.
- 📡 **WiFi and Bluetooth control** via a smartphone or controller.
- 🛑 **Obstacle avoidance sensors** to navigate autonomously.
- 🔄 **Real-time monitoring** for emergency response teams.
- 💰 **Very cheap** – cost-effective emergency solution. 
- 🏋️ **Super lightweight** – easy to transport and deploy.
- ⚡ **Moves faster than other robots**, at least **40km/h**.
- 🔍 **Can navigate complex terrains** such as **super small caves, narrow entrances, etc.** 
- 📦 **Can deliver at least 5kg of supplies**: food, medicine, medkits, collapsible emergency tents, etc.
- 👶 **Ideal for saving babies and small animals**: birds, cats, dogs, etc.
- 🌊 **Waterproof and all-terrain capability** – moves in **harsh terrain conditions** (high water levels) and **harsh weather** (high winds).

## 🛠️ Tech Stack
- **Hardware:** Arduino, Ultrasonic Sensors, Camera Module, WiFi Module (ESP8266/ESP32)
- **Software:** Arduino IDE, C++, Python (for camera streaming), Swift for app development
- **Control Interface:** Smartphone App (via WiFi & Bluetooth)

## 📦 Installation & Setup
### **1️⃣ Download & Install Requirements**
1. **Download Arduino IDE** from [Arduino Website](https://www.arduino.cc/en/software).
2. Install necessary libraries:
   ```bash
   Arduino Library Manager > Install WiFi, Servo, and Camera libraries
   ```
3. Connect your **Arduino board** to your PC via USB.

### **2️⃣ Clone the Repository**
```bash
git clone https://github.com/TienNguyenTech/ResBot.git
cd ResBot
```

### **3️⃣ Upload Code to Arduino**
1. Open **`ResBot.ino`** in **Arduino IDE**.
2. Select the correct **board and port** under *Tools > Board*.
3. Click **Upload** to flash the code onto the robot.

### **4️⃣ Connect to WiFi & Control**
1. Power on ResBot.
2. Open the **mobile app** or a browser and connect to ResBot’s **WiFi or Bluetooth network**.
3. Control movement and view live camera feed.

## 📝 How It Works
1. The **WiFi & Bluetooth modules** allow remote control via phone or controller.
2. The **camera module** streams live video.
3. **Ultrasonic sensors** detect obstacles and reroute the robot.
4. **Emergency supplies** are carried and delivered to affected areas.

## 🌟 Future Improvements
- ✅ **AI-based navigation** for autonomous delivery.
- 🔔 **Emergency alerts** via cloud integration.
- 📍 **GPS tracking** for precise location delivery.

## 💼 Why This Project?
ResBot is a **real-world solution** demonstrating:
- **Embedded systems programming (Arduino, C++)**.
- **IoT & wireless communication**.
- **Obstacle avoidance & real-time control**.

## 📩 Connect with Me
- 🌐 [Portfolio](https://your-portfolio.com)
- 🔗 [LinkedIn](https://linkedin.com/in/tomng9)
- 🐙 [GitHub](https://github.com/TienNguyenTech)
- 📧 Email: tienng39@gmail.com
