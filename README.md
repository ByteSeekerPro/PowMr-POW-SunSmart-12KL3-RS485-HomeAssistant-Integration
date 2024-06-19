PowMr-POW-SunSmart-12KL3-RS485-HomeAssistant-Integration

HomeAssistant ESPHome / RS485 Integration for all Inverters of the type
- POW-SunSmart 8KL3
- POW-SunSmart 10KL3
- POW-SunSmart 12KL3 - tested with this one

- some SRNE X3 Models - I don't know the models, but they should also work because the MODBUS communication protocol documentation I used is from SRNE.

What do you need?

Hardware
- 1 x ESP32 NodeMCU https://amzn.to/45ssngF
- 1 x TTL to RS485 Converter https://amzn.to/4c6Vhpd
- 1 x LAN Kabel RJ45

Software
- HomeAssistant
- ESPHome as HomeAssistant Integration

Instead of the WiFi dongle, this adapter based on an ESP32 is connected to the WiFi interface of the inverter.

ESP32 WROOM Pinout (38 Pin)

Pins used:
3V3 - VCC (TTL to RS485)
GND - GND (TTL to RS485)
GPIO16 (RX2) - RXD (TTL to RS485)
GPIO17 (TX2) - TXD (TTL to RS485)

![image](https://github.com/ByteSeekerPro/PowMr-POW-SunSmart-12KL3-RS485-HomeAssistant-Integration/assets/173205372/89d6227d-ca61-4aeb-9a73-7d3ea7fd3665)

TTL to RS485 Converter

![image](https://github.com/ByteSeekerPro/PowMr-POW-SunSmart-12KL3-RS485-HomeAssistant-Integration/assets/173205372/e1120a85-f1ab-4ca5-85ef-10b266e50600)



