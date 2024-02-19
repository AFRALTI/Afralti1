# Afralti1
# STM32 BluePill with LoRa (RFM95W) - Design Document
# Overview
This document provides a brief overview and hardware connection details for integrating STM32 Blue Pill with RFM95 LoRa module. This board is designed for LoRa & LoRaWAN training  purposes.

# Components
STM32 Bluepill
LoRa Module (RFM95W)
BMP/BME280
DHT22
TP4056


Hardware Connection

| STM32 BLUEPILL  | RFM96 |
| ------------- | ------------- |
| PA6  |MISO  |
| PA7 | MOSI  |
| PA5 | SCK  |
| PA4 | NSS  |
| PB0 | RST  |
| PA3 | DIO0  |
| PB5 | DIO1  |
| GND | GND  |
| 3.3V | 3.3V  |

| STM32 BLUEPILL  | BME/BMP280 |
| ------------- | ------------- |
| 3.3V  |VIN  |
| GND  |GND  |
| PB6 |SCL  |
| PB7  |SDA  |

# DHT 22
- Specifications:
Operating Voltage: 3.5V to 5.5V
Operating Current: 0.3mA (measuring) and 60uA (standby)
Temperature Range: -40°C to 80°C
Humidity Range: 0% to 100%
Resolution: Both temperature and humidity have 16-bit resolution.
Accuracy: ±0.5°C for temperature and ±1% for humidity.
- Reference Materails
([Reference Datasheet](https://components101.com/sensors/dht22-pinout-specs-datasheet))

- Images & Diagrams
| DHT 22 IMAGE | schematic Connection|
|---------|---------|
|![DHT22](https://github.com/AFRALTI/Afralti1/assets/52659391/ffd94295-6916-4dbe-9122-dae9080a28d4) | ![Connection Diagram](https://github.com/AFRALTI/Afralti1/assets/52659391/e056e77f-3e4f-42d4-b637-336897a48d8c) |


- Pin Mapping

| STM32 BLUEPILL  | DHT22|
| ------------- | ------------- |
| 3.3V  |VCC  |
| GND  |GND  |
| PB9  |DATA  |

# Schematic Design
![image](https://github.com/AFRALTI/Afralti1/assets/52659391/4677c34d-099d-4ee8-9639-3d7e40def0c3)

![image](https://github.com/AFRALTI/Afralti1/assets/52659391/f4e11703-c5c6-4185-8a40-464b86bed5bc)
![image](https://github.com/AFRALTI/Afralti1/assets/52659391/4a7a6d80-2d2c-4ec7-b0b9-aacea85831a1)

# 3D View
![image](https://github.com/AFRALTI/Afralti1/assets/52659391/9cfc41b2-7c3d-4166-a460-a420234cc51b)
![image](https://github.com/AFRALTI/Afralti1/assets/52659391/7eb5e32d-48c8-407d-b460-6c648e13df68)




