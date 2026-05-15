<div align="center">

<h1>Zero-VA</h1>

<img width="600" height="800" alt="20260509_082448" src="https://github.com/user-attachments/assets/895305f6-6efc-449d-80ae-98b0774309f2" />

<br>

<a href="https://realdeco.github.io/Zero-VA/Zero-VA-Sendspin/" target="_blank">
  <img src="https://img.shields.io/badge/FIRMWARE-OPEN%20WEB%20INSTALLER-111827?style=for-the-badge&logo=googledocs&logoColor=white" alt="Open Firmware Installer">
</a>

</div>

# A minimal Voice Assistant for Home Assistant.


This project uses an ESP32-S3 Zero together with a WeAct audio codec module that includes:
- a speaker amplifier (such as the MAX98357)
- a microphone (such as the INMP441)
- an ES8311 audio codec

Together, these components create a compact Voice Assistant for ESPHome that integrates with Home Assistant.

## Parts

| Part | Link |
|------|------|
| ESP32-S3 Zero | https://www.aliexpress.com/item/1005009890203011.html |
| WeAct Mono Audio Codec Module | https://www.aliexpress.com/item/1005010466805014.html |
| Speaker (Example, 4Ω recommended) | https://www.aliexpress.com/item/1005007614290956.html |

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

## Firmware

<a href="https://realdeco.github.io/Zero-VA/Zero-VA-Sendspin/" target="_blank">
  <img src="https://img.shields.io/badge/FIRMWARE-OPEN%20WEB%20INSTALLER-111827?style=for-the-badge&logo=googledocs&logoColor=white" alt="Open Firmware Installer">
</a>

