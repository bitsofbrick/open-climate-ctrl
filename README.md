# 🏡 Open-Climate-Ctrl

🟡 **Status:** WIP &nbsp;|&nbsp; 🟢 **License:** MIT &nbsp;|&nbsp; 🔵 **Platform:** ESP32

Open-source microclimate controller for greenhouses based on ESP32.

## 🎯 Goal
Control the temperature, humidity and acidity of the soil, the temperature and humidity of the air.
Automate temperature, humidity, lighting and irrigation for small-scale gardens and indoor farms.

## 🚧 Status
- [ ] Hardware design (schematics)
- [x] Core modules selected & tested
- [ ] Sensor integration (in progress)
- [ ] Web dashboard
- [ ] Bluetooth WiFi provisioning
- [ ] Documentation

## 🔧 Tech Stack
- **MCU:** ESP32
- **Firmware:** Arduino IDE

## 📦 Hardware

### Controller
- **ESP32 Piranha v2** — [iarduino.ru](https://iarduino.ru/shop/boards/piranha-esp32.html)
  - Tested
  - WiFi + Bluetooth
  - Dual core, 240 MHz

### Actuators
- **4-Channel I2C Relay Module** — [iarduino.ru](https://iarduino.ru/shop/Expansion-payments/power-key-4n-i2c.html)
  - I2C addressable (saves GPIO pins)
  - Controls: heater, humidifier, lights, pump

### Sensors
- **DHT22** — temperature & humidity (air)
- **DS18B20** — waterproof temperature sensor (1m cable) — [iarduino.ru](https://iarduino.ru/shop/Sensory-Datchiki/datchik-temperatury-ds18b20-1-metr-vodonepronicaemyy.html)
- **Capacitive Soil Moisture** — [iarduino.ru](https://iarduino.ru/shop/Sensory-Datchiki/datchik-vlazhnosti-pochvy-emkostnoy.html)
  - Corrosion-resistant
  - Analog output

### Planned
- [ ] Light sensor (BH1750)
- [ ] CO2 sensor (MH-Z19B)
- [ ] Real-time clock (DS3231)
- [ ] OLED display (0.96" I2C)

## 🔌 Power
- Input: 5V/2A (micro-USB or external)
- Relays: separate 5-12V supply recommended

## 📐 Wiring Diagram
*Coming soon*

## 🚀 Quick Start
*Guide will be added after firmware stabilization*

## 📄 License
**MIT License** — use, modify, share, even commercially. Just keep this notice.
