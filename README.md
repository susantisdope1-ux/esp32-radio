# ESP32-S3 Internet Radio

The **ESP32-S3 Internet Radio** is a small desktop radio that can connect to radio stations over the internet using a Wi-Fi connection. This design gives you the ability to enjoy listening to thousands of radio stations from all over the world, with crystal-clear digital audio, unlike conventional FM radios whose reach is limited by geographical factors. The project makes use of a custom-made PCB board, a 3D printed case, and basic controls in creating this internet radio device for your desktop or workplace.

This project uses the **ESP32-S3** microcontroller that connects to the internet, downloads the radio stream from the internet, decodes the audio, and outputs digital audio to the **MAX98357 I2S amplifier**. The amplifier feeds the audio to the **4Ω speaker**. The information such as the currently playing station is shown on a **0.96-inch OLED display**. The station and the volume levels can be controlled using the **rotary encoder**

 A PCB was made in **EasyEDA Pro** to keep the design small and cut out unnecessary connections. An enclosure was designed in **Fusion 360**, which was 3D-printed in PLA to produce an elegant design for use on a desk that securely houses all the components.
 
---

# Characteristics

- ESP32-S3 Wi-Fi Microcontroller Board
- Internet Radio Streaming Capabilities
- MAX98357A I2S Digital Audio Amplifier
- 0.96" I2C OLED Display Module
- 5V DC Power Supply

---

# Project Images

## Schematic

<p align="center">
  <img width="1101" height="647" alt="Screenshot 2026-10-31 201057" src="https://github.com/user-attachments/assets/9867eb2d-179a-438e-9adc-1fd5a8e0d49e" />

</p>

---

## PCB Layout

<p align="center">
  <img width="572" height="646" alt="Screenshot 2026-10-31 202431" src="https://github.com/user-attachments/assets/825d9bb3-be4b-4e38-b4a6-13d400604fac" />

</p>

---

## 3D PCB View

<p align="center">
  <img width="907" height="722" alt="Screenshot 2026-10-31 202501" src="https://github.com/user-attachments/assets/ab27e3e6-7127-4f0f-b808-865a848e467b" />

</p>

---



# Bill of Materials (BOM)

## Bill of Materials (BOM)

| Qty | Component | Purchase Link | Approx. Cost |
|:---:|-----------|---------------|------------:|
| 1 | ESP32-S3 DevKit (N16R8 Recommended) | https://www.aliexpress.com/wholesale?SearchText=ESP32-S3+N16R8 | $10.00 |
| 1 | MAX98357A I2S Amplifier Module | https://www.aliexpress.com/wholesale?SearchText=MAX98357A | $2.20 |
| 1 | 0.96" OLED Display (I2C) | https://www.aliexpress.com/wholesale?SearchText=0.96+OLED+I2C | $2.50 |
| 1 | EC11 Rotary Encoder | https://www.aliexpress.com/wholesale?SearchText=EC11+Rotary+Encoder | $0.80 |
| 1 | 4Ω 3W Speaker | https://www.aliexpress.com/wholesale?SearchText=4ohm+3w+speaker | $1.50 |
| 1 | DC Barrel Jack | https://easyeda.com/component/search/DC005 | $0.20 |
| 1 | 2-Pin Screw Terminal (5.08mm) | https://easyeda.com/component/search/Terminal%20Block | $0.15 |
| 3 | 2.54mm Pin Header | https://easyeda.com/component/search/Pin%20Header | $0.10 |
| 1 | Custom PCB | JLCPCB | $4.00 |


---

# PCB Manufacturing Cost

The PCB was manufactured through **JLCPCB** using the standard 2-day production service. The project was fabricated on a custom PCB designed in EasyEDA Pro and shipped using DHL Express.

| Item | Price |
|------|------:|
| PCB Fabrication | **$4.00** |
| PCB Build Time | **2 Days** |
| Surface Finish | Included |
| Shipping (DHL Express) | **$35.34** |
| **Total Cost** | **$39.34** |

> **Note:** Prices shown are from my order and may vary depending on shipping location, PCB quantity, and manufacturing options.

---

# Software

The firmware has been created with the help of the **Arduino Framework** for the ESP32-S3 microcontroller. When powered on, the device automatically connects to the specified Wi-Fi network and streams the selected internet radio station from those available in the list of preset stations.
---

# Tools Used

- EasyEDA Pro
- Arduino IDE
- JLCPCB

---

# MADE BY SAN JU GAM FOR HACK CLUB

## This project is open-source
