# Cleansphere- #
Welcome to CleanSphere, an open-source project dedicated to fostering sustainable practices through advanced environmental monitoring. This repository houses the codebase and design files for a comprehensive system that integrates an ESP32 microcontroller, DHT22 temperature and humidity sensor,MQ-135 gas sensor, and a user-friendly CADIO dashboard.

## List of parts required!
* MQ135 Air Quality sensor
* DHT 22 temperature and humidity sensor
* ESP8226MOD/ESP32
* 3D Printed casing

## Wiring diagram for the ESP32
<img width="474" alt="Image20240106070325" src="https://github.com/Clean-Sphere/Cleansphere-/assets/155823427/06954a58-d221-4f1e-8dc7-27c299034727">

### These are the connections for each sensor:

### DHT22

* VCC: Connect to the power supply (3.3V or 5V).
* GND: Connect to ground.
* DATA: Connect to a digital pin on your microcontroller.
* NC: No connect.

### MQ-135
* VCC: Connect to the power supply (5V).
* GND: Connect to ground.
* AOUT: Connect to an analog pin on your microcontroller.

### To measure air quality, temperature, and humidity with these sensors, you'll need to Flash the [CADIO FIRMWARE](https://egycad.com/cadio/docs/category/firmware/ "Named link title") onto the ESP8266/ESP32 Via [ESP Flash Tool](https://www.espressif.com/en/support/download/other-tools "Named link title") and configure the connection and pins via the CADIO mobile app

## 3D Printed case!
