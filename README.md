# ESP32-Smart-Data-Logger-with-Google-Sheets-Integration
It is a smart environmental monitoring system, which is constructed with ESP32 microcontroller. It takes real-time data from sensors to check smoke concentration (PPM), heart rate, and noise levels, furthermore continuously logs this data to Google Sheets through an App Script API for visualization and analysis.
The Arduino card is coded using C++ programming language for sensor data processing by using Arduino IDE to receive the sensors’ readings. The ESP32-WROOM is coded for WiFi connection to transfer data from the Arduino to the spreadsheet
The hardware connections:-
ESP to Arduino connections:
3.3V (ESP) → 3.3V (Arduino)
GND (ESP) → GND (Arduino) 
RX (ESP) → TX/3 (Arduino) 
TX (ESP) → RX/2 (Arduino)
Ky039 heartbeat sensor:
GND (-ve) → GND (Arduino) 
VCC → 5V (Arduino) 
Data → A1 (Arduino)
MQ-135 air quality (smoke sensor):
GND → GND (Arduino)
VCC → 5V (Arduino) 
A0 → A0 (Arduino)
Max9814 noise sensor:
GND → GND (Arduino)
VDD → 5V (Arduino)
Out → A2 (Arduino)
Rechargeable Lithium-ion batteries:
(-ve) pole → GND (System)
(+ve) pole → 5V (Arduino)
