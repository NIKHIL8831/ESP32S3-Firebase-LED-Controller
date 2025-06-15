# ESP32S3-Firebase-LED-Controller
This project controls the inbuilt NeoPixel LED on an ESP32-S3 board via Firebase Realtime Database and a simple web app.

##  Web App Features
- Turn LED ON/OFF using buttons
- Real-time Firebase sync
- LED status display

##  ESP32 Features
- Reads `LED_STATUS` from Firebase every 5 seconds
- Lights Green LED if status is "ON", turns OFF if "OFF"
- Uses Firebase ESP Client Library and Adafruit NeoPixel
- # #Tools Used
- ESP32-S3 board
- Firebase Realtime Database
- HTML, JavaScript
- Arduino IDE
