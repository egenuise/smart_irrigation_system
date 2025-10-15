# Smart Irrigation System by Evan Genuise
## About
I’m building a Smart Irrigation System as a way to learn more about embedded systems and practical agriculture applications. This project uses an STM32 Nucleo-F103RB microcontroller, a capacitive soil moisture sensor, and a relay-controlled water pump to automatically water plants based on soil moisture levels.

My goals with this project are to:
- Explore how automated irrigation systems work.
- Practice working with ADC inputs and GPIO outputs on STM32 microcontrollers.
- Gain experience integrating sensors, relays, and optional displays.
- Create a simple, practical tool for plant care that can be expanded with additional sensors or wireless monitoring.

This is still a work in progress, but I’m sharing it here both as documentation of my process and in case it’s useful for anyone interested in microcontroller-based agriculture or automation projects.

## Features
- Read soil moisture via ADC input.
- If moisture falls below a threshold → activate pump for a set duration.
- Display soil percentage on a screen or send data to a serial monitor.

## BOM
- Capacitive Soil Moisture Sensor
- Relay Module or MOSFET
- Small water pump or solenoid valve
- LCD/OLED display (optional)
- Power supply (5–12 V depending on your pump)

## Upgrade Ideas
- Add a Bluetooth or Wi-Fi module (ESP8266) to monitor data remotely.
- Add temperature and humidity sensors (DHT22 or BME280).