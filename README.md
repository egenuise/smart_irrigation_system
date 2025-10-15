# Smart Irrigation System by Evan Genuise
## About
Goal: Automatically water plants based on soil moisture levels.

## Features
- Read soil moisture via ADC input.
- If below threshold → activate pump for a set duration.
- Display soil % on screen or send to serial monitor.

## BOM
- Soil moisture sensor (capacitive preferred over resistive)
- Relay module or MOSFET (to switch a water pump)
- Small water pump or solenoid valve
- LCD/OLED display (optional)
- Power supply (5–12 V depending on your pump)

## Upgrade ideas:
- Add temperature and humidity sensors (DHT22 or BME280).
- Add a Bluetooth or Wi-Fi module (ESP8266) to monitor data remotely.