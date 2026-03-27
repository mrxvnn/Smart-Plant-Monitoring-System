# Smart-Plant-Monitoring-System

**Features**
Sensors:
Soil Moisture Sensor → reads water content (analog).
DHT11 → reads temperature & humidity.

Display:
OLED SSD1306 shows real-time Moisture %, Temp, and Humidity.

LED Alerts (Tri-color Common Anode):
Green → normal
Blue → slightly dry (warning)
Red → critical (too dry / extreme temp)

Buzzer:
Only ON in critical conditions.

**Components:**
Arduino Uno R3
Soil Moisture Sensor
DHT11 Sensor
SSD1306 OLED Display
Tri-Color LED (Common Anode)
Buzzer
Jumper Wires
Breadboard

**Expected Outcome**
OLED displays Moisture %, Temperature, and Humidity.
Tri-color LED changes according to soil and temperature conditions.
Buzzer sounds during critical conditions.
Arduino runs the system independently without WiFi.

**Applications**
Smart gardening and irrigation
Indoor plant monitoring
Educational STEM projects
Agriculture and farming assistance

**How to Use**
Assemble all components as per wiring table.
Upload the Arduino code via Arduino IDE.
Observe real-time values on the OLED display.
Check LED and buzzer alerts when moisture levels or temperature exceed safe limits.
Adjust soil moisture sensor placement to test different conditions.
