#### ESP32 Firebase Camera Streaming

### Overview

This project utilizes the ESP32 microcontroller along with the Firebase Realtime Database (RTDB) to capture images using an attached camera and publish them to the database. The images are encoded in Base64 format and stored in the RTDB. This can be useful for remote monitoring applications or capturing images at specific intervals.

### Prerequisites

ESP32 board with Arduino support
Camera compatible with ESP32
WiFi network credentials (SSID and password)
Firebase project with an enabled RTDB
Firebase API key, user email, and password

### Installation

> 1. Arduino IDE Setup
Make sure you have the Arduino IDE installed on your computer. Follow the official guide to set up the Arduino IDE.

> 2. Install ESP32 Board Support
Install the ESP32 board support by following the instructions here.

> 3. Install Required Libraries
Install the following libraries using the Arduino Library Manager:

Firebase ESP32: Firebase ESP32 by firebase`

> 4. Set Up Firebase
Create a Firebase project on the Firebase Console.
Obtain the API key, user email, and password.
Create an RTDB and note the database URL.

> 5. Update Code Configuration
Replace the placeholders (****) in the code with your WiFi credentials (ssid and password).
Replace the placeholders (USER_EMAIL, USER_PASSWORD, API_KEY, DATABASE_URL) with your Firebase authentication and database information.