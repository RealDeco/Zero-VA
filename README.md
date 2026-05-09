# Zero-VA

<p align="center">
  <img width="600" height="800" alt="20260509_082448" src="https://github.com/user-attachments/assets/895305f6-6efc-449d-80ae-98b0774309f2" />
</p>

A minimal Voice Assistant for Home Assistant.

This project uses an ESP32-S3 Zero together with a WeAct audio codec module that includes:
- a speaker amplifier (such as the MAX98357)
- a microphone (such as the INMP441)
- an ES8311 audio codec

Together, these components create a compact Voice Assistant for ESPHome that integrates with Home Assistant.

## Parts

- ESP32-S3 Zero  
  https://www.aliexpress.com/item/1005009890203011.html

- WeAct Mono Audio Codec Module  
  https://www.aliexpress.com/item/1005010466805014.html

- Any speaker, 4ohm will be louder. (example)
  https://www.aliexpress.com/item/1005007614290956.html

## Pinout

| ESP32-S3 Zero | WeAct Module |
|----------------|---------------|
| GND            | GND           |
| 3V3            | VCC           |
| GPIO1          | SD            |
| GPIO2          | DI            |
| GPIO3          | WS            |
| GPIO4          | DO            |
| GPIO5          | BCK           |
| GPIO6          | MC            |
| GPIO7          | SDA           |
| GPIO8          | SCL           |
