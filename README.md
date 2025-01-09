🚀 ESP32 + Adafruit IO + IFTTT: Smart Servo & Light Control

Welcome to the ESP32 Smart Servo & Light Control project! 🎉 This project combines the power of the ESP32, Adafruit IO, and IFTTT to create a smart system that controls servo motors and lights remotely via the web or Google Assistant. 🌐✨

🛠️ Features

Remote Control: Operate servo motors and lights from anywhere using Adafruit IO. 🌍

Google Assistant Integration: Seamlessly control devices using voice commands. 🎙️🤖

Real-time Updates: Stay in sync with the system's state via IFTTT and Adafruit IO. 🔄

Compact & Efficient: Designed for a DIY-friendly experience. 🛠️💡

🖼️ Project Overview

This project connects:

ESP32: The brain of the system.

Adafruit IO: For managing device states and communication.

IFTTT: To bridge Adafruit IO with Google Assistant.

🧩 How it works:

Google Assistant sends a command to IFTTT.

IFTTT triggers an Adafruit IO feed update.

ESP32 reads the feed and moves the servo motor or toggles the light.

📋 Prerequisites

Before diving in, ensure you have:

🔧 ESP32 Development Board

📶 Wi-Fi Network (with credentials)

🛠️ Servo Motor

💡 Light or equivalent device (optional)

⚡ Basic wiring setup

🌐 Adafruit IO & IFTTT accounts

🔌 Hardware Setup

Connect your servo motor to the ESP32:

Signal pin to GPIO (e.g., D13).

Power and ground to the appropriate pins.

If using a light, connect it via a relay to the ESP32.

Power up the ESP32 and verify connections. ✅

💻 Software Setup

Install the following libraries in your Arduino IDE:

WiFi.h

AdafruitIO_WiFi.h

ESP32Servo.h

Configure your code:

Replace Wi-Fi and Adafruit IO credentials.

Upload the code to your ESP32. 🚀

🤖 Google Assistant Integration via IFTTT

Create an IFTTT account and connect Google Assistant.

Set up two applets:

Turn ON the device: Sends "1" to the Adafruit IO feed.

Turn OFF the device: Sends "0" to the Adafruit IO feed.

Link these applets to your Adafruit IO feeds.

📚 Usage

Open the Adafruit IO dashboard.

Use buttons to control the servo or light.

Alternatively, say commands like "Turn on the light" or "Turn off the light" to Google Assistant.

🎉 Enjoy your smart system in action!

🎯 Future Enhancements

Add more devices for broader control. 📡

Integrate more triggers using IFTTT. ⚡

Enhance with sensors for automation. 🤖

📸 Screenshots

Coming soon! Share yours by creating a pull request. 📷✨

📝 License

This project is open-source under the MIT License. Feel free to use, modify, and share! 🌟

🙌 Credits

Developed by ProbityRaj with ❤️ and passion for DIY projects. 💡✨

