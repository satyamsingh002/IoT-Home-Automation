 🏠 IoT Home Automation System

A smart and affordable home automation system using **ESP32**, **Google Assistant**, and **IoT protocols**, allowing users to control home appliances like lights and fans via voice commands and mobile app.

------------------------------------------------------------------------------------------------------
🚀 Features

- ✅ Voice control using **Google Assistant**
- ✅ Control appliances remotely over Wi-Fi
- ✅ Real-time feedback (LED ON/OFF status)
- ✅ Supports multiple devices (Light, Fan, etc.)
- ✅ Power-efficient and affordable hardware

--------------------------------------------------------------------------------------------------------------------------------------------------------------------
 🛠️ Tech Stack

| Technology      | Description                    |
|----------------|--------------------------------|
| ESP32          | Microcontroller for Wi-Fi      |
| Arduino IDE    | Programming environment         |
| IFTTT          | Google Assistant integration    |
| Blynk / Firebase | Optional control platform     |
| Relay Module   | Hardware switching              |

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

🧰 Hardware Requirements

- ESP32 Dev Board
- Relay Module (1/2/4 channel)
- Light bulb or Fan
- Jumper wires
- Breadboard or PCB
- Internet connection (Wi-Fi)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

📱 Software Requirements

- Arduino IDE
- Blynk App / Google Home
- IFTTT Account
- ESP32 Board package

--------------------------------------------------------------------------------------------------------------------------------------------------------------------


🔌 How It Works

1. User gives voice command to Google Assistant  
2. IFTTT triggers a WebHook URL  
3. ESP32 receives request and switches relay  
4. Appliance is turned ON/OFF based on command

--------------------------------------------------------------------------------------------------------------------------------------------------------------------


 ⚙️ Setup Instructions

### 🔧 1. Flash Code to ESP32
- Open Arduino IDE
- Select board: `ESP32 Dev Module`
- Upload the code

### 🌐 2. Connect to Wi-Fi
- Edit the code to add your Wi-Fi SSID and Password

```cpp
const char* ssid = "YOUR_WIFI_NAME";
const char* password = "YOUR_WIFI_PASSWORD";
