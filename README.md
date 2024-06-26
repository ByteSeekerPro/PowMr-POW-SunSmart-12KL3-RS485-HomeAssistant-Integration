!!! This repository is currently being set up !!!

The yaml file is in progress... :-)

PowMr-POW-SunSmart-12KL3-RS485-HomeAssistant-Integration

HomeAssistant ESPHome / RS485 Integration for all Inverters of the type
- POW-SunSmart 8KL3
- POW-SunSmart 10KL3
- POW-SunSmart 12KL3 - tested with this one

- some SRNE X3 Models - I don't know the models, but they should also work because the MODBUS communication protocol documentation I used is from SRNE.

What do you need?

Hardware
- 1 x ESP32 NodeMCU https://amzn.to/45ssngF or ESP32 NodeMCU with external antenna https://amzn.to/3RLFtjz
- 1 x TTL to RS485 Converter https://amzn.to/4c6Vhpd
- 1 x LAN Cable RJ45 (only a half of this)
- 1 x Housing 100mm x 60mm x 25mm https://amzn.to/3KZAoA7

Software
- HomeAssistant
- ESPHome as HomeAssistant Integration

This adapter, based on an ESP32, can be connected to the WiFi or RS485 interface of the inverter.

ESP32 WROOM Pinout (38 Pin)

ESP is powered over USB.

Pins used:
- 3V3 - VCC (TTL to RS485)
- GND - GND (TTL to RS485)
- GPIO16 (RX2) - TXD (TTL to RS485)
- GPIO17 (TX2) - RXD (TTL to RS485)

![image](https://github.com/ByteSeekerPro/PowMr-POW-SunSmart-12KL3-RS485-HomeAssistant-Integration/assets/173205372/89d6227d-ca61-4aeb-9a73-7d3ea7fd3665)

TTL to RS485 Converter

Pins used:
- A+ - Pin7 RJ45 Cable
- B- - Pin8 RJ45 Cable

![image](https://github.com/ByteSeekerPro/PowMr-POW-SunSmart-12KL3-RS485-HomeAssistant-Integration/assets/173205372/e1120a85-f1ab-4ca5-85ef-10b266e50600)

PowMr Inverter Wifi Port / RS485

![image](https://github.com/ByteSeekerPro/PowMr-POW-SunSmart-12KL3-RS485-HomeAssistant-Integration/assets/173205372/b7228ac0-712f-4562-a4b0-f1323dc0dc91)

Wiring Diagram

![image](https://github.com/ByteSeekerPro/PowMr-POW-SunSmart-12KL3-RS485-HomeAssistant-Integration/assets/173205372/d31c9d7d-cf2c-4d49-8648-69220d60f019)

Fully assembled

![ESP_2](https://github.com/ByteSeekerPro/PowMr-POW-SunSmart-12KL3-RS485-HomeAssistant-Integration/assets/173205372/a12b9439-9464-417b-a441-f6ff9f8dbaa5)
![ESP_3](https://github.com/ByteSeekerPro/PowMr-POW-SunSmart-12KL3-RS485-HomeAssistant-Integration/assets/173205372/78d0bb03-6fe4-405e-86eb-9a2feb9b1d3b)
