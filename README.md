# 🔌 ESP8266 LED Brightness Control  

A simple web-based **ESP8266 control panel** to adjust LED brightness using a slider.  

🌐 **Live Demo:** [ESP8266 Control Panel](https://aj-adi.github.io/ESP8266-Slider/)  

## 📌 Features  
✅ Control LED brightness remotely using a web-based slider  
✅ ESP8266 communicates with the webpage to receive brightness values  
✅ Simple and lightweight implementation  

## 📂 Project Structure  
├── control_led_brightness.ino # Arduino code for ESP8266 

├── index.html # Web interface with slider 

├── README.md # Documentation

## 🚀 How to Use  

### 1️⃣ Upload the Arduino Code to ESP8266  
1. Install the **ESP8266 board package** in the Arduino IDE.  
2. Connect your ESP8266 and upload `control_led_brightness.ino`.  

### 2️⃣ Host the Webpage  
- The `index.html` file is hosted via **GitHub Pages**:  
  👉 [ESP8266 Slider](https://aj-adi.github.io/ESP8266-Slider/)  

- You can also save `index.html` locally and open it in a browser.  

### 3️⃣ Connect ESP8266 to the Web Interface  
- Ensure ESP8266 is connected to WiFi.  
- Open the webpage and adjust the slider to change LED brightness.  

## 🔧 Requirements  
- **ESP8266 (NodeMCU or similar)**  
- **Arduino IDE** with ESP8266 board support  
- **Basic LED circuit setup**  

## 🤝 Contributing  
Feel free to improve this project by adding features like:  
🔹 Multiple LED control  
🔹 Responsive UI improvements  
🔹 MQTT integration for IoT  

## 📞 Contact  
For any questions, feel free to contact me on Discord - **theaj.**  
