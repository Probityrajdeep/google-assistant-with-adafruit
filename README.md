<h1 align="center" style="font-size: 3rem; color: #0078D7;">🌐 Google Assistant-Controlled ESP32 with Adafruit IO 🌟</h1>

<p align="center" style="font-size: 1.2rem; color: #555;">Ever dreamt of controlling your devices with your voice? 🤖✨<br>
With this project, we're combining the power of <b>Google Assistant</b>, <b>Adafruit IO</b>, and the amazing <b>ESP32</b> to create a smart system that responds to your commands! 🛠️💡</p>

---

<h2 style="color: #D2691E;">🧐 What’s This About?</h2>
<p>This project allows you to:</p>
<ul style="font-size: 1rem; line-height: 1.5;">
  <li>1️⃣ Control <b>Servo Motors</b> with Google Assistant commands.</li>
  <li>2️⃣ Manage a <b>Main Power Switch</b> (Light) effortlessly.</li>
  <li>3️⃣ Use the seamless connectivity of <b>Adafruit IO</b> to bridge the gap.</li>
  <li>4️⃣ All with the versatility of an ESP32! 🕹️</li>
</ul>

---

<h2 style="color: #8A2BE2;">🔧 Hardware Requirements</h2>
<ul>
  <li>🖥️ <b>ESP32</b>: The heart of the system.</li>
  <li>⚙️ <b>Servo Motors</b>: Control your devices.</li>
  <li>💡 <b>Relay Module</b> (optional): To manage main power (lights).</li>
  <li>🌐 <b>Wi-Fi Network</b>: Stable connection required.</li>
</ul>

---

<h2 style="color: #32CD32;">🛠️ How It Works</h2>
<p>🎤 <b>Google Assistant</b> ➡️ <b>IFTTT/Zapier</b> ➡️ <b>Adafruit IO</b> ➡️ <b>ESP32</b></p>
<p>Commands sent to Google Assistant trigger actions in Adafruit IO, which are then processed by the ESP32 to control connected devices. 🚀</p>

<ul>
  <li>Servo 1 (L Motor): 🔄 Operates between <b>180° (ON)</b> and <b>200° (OFF)</b>.</li>
  <li>Servo 2 (M Motor): 🔄 Operates between <b>30° (ON)</b> and <b>80° (OFF)</b>.</li>
  <li>Main Power (Light): 💡 Toggle ON/OFF.</li>
</ul>

---

<h2 style="color: #FF4500;">🎯 Features</h2>
<ul>
  <li>✨ Voice-controlled actions.</li>
  <li>✨ Cloud-based interface with <b>Adafruit IO</b>.</li>
  <li>✨ Precision control of servo motors.</li>
  <li>✨ Simple to set up and use.</li>
</ul>

---

<h2 style="color: #4682B4;">🚀 Quick Start</h2>
<ol>
  <li><b>Setup Adafruit IO:</b>
    <ul>
      <li>Create feeds: <code>servo_L_button</code>, <code>servo_M_button</code>, and <code>main_power</code>.</li>
      <li>Get your <b>Adafruit IO Key</b> and <b>Username</b>.</li>
    </ul>
  </li>
  <li><b>Program the ESP32:</b>
    <ul>
      <li>Use the provided code (see the repo).</li>
      <li>Update with your Wi-Fi, Adafruit IO credentials, and GPIO pin numbers.</li>
    </ul>
  </li>
  <li><b>Create Applets (IFTTT or Zapier):</b>
    <ul>
      <li>Link Google Assistant to Adafruit IO.</li>
      <li>Create applets for <i>Turn ON/OFF Light</i>, <i>Turn ON/OFF Servo L</i>, and <i>Turn ON/OFF Servo M</i>.</li>
    </ul>
  </li>
  <li><b>Test it Out:</b>
    <ul>
      <li>Say commands like <i>"Turn on light"</i> or <i>"Switch off Servo L."</i></li>
      <li>Watch the magic happen! 🎩✨</li>
    </ul>
  </li>
</ol>

---

<h2 style="color: #DA70D6;">🖼️ Project Overview</h2>
<p align="center">
  <img src="https://via.placeholder.com/800x400" alt="Project Setup" style="border: 2px solid #555; border-radius: 10px;">
</p>
<p align="center"><i>*Diagram of ESP32 connected to servo motors and relay.*</i></p>

---

<h2 style="color: #FF6347;">🛡️ Security Tips</h2>
<ul>
  <li>🔐 Keep your Adafruit IO key private.</li>
  <li>🔐 Use a secure Wi-Fi network.</li>
  <li>🔐 Regularly monitor your applets for any unwanted triggers.</li>
</ul>

---

<h2 style="color: #FFD700;">🌟 Why This Project Rocks</h2>
<ul>
  <li>✅ Hands-free control of devices.</li>
  <li>✅ Learn about IoT, Google Assistant, and Cloud Integrations.</li>
  <li>✅ Fun, creative, and super cool! 😎</li>
</ul>

---

<p align="center">
  💡 <b>Want to contribute or have questions?</b>  
  Feel free to drop an issue or contribute via PR. Let’s make it even better!  
</p>

<p align="center">
  🔗 <a href="https://github.com/Probityrajdeep/google-assistant-with-adafruit" style="color: #1E90FF; text-decoration: none;">Explore the Code & Details</a>
</p>
