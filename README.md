# ESP32-S3 Internet Radio

The **ESP32-S3 Internet Radio** is a compact desktop radio that streams online radio stations over a Wi-Fi connection. Unlike traditional FM radios, which are limited by broadcast range and signal quality, this project allows you to listen to thousands of radio stations from around the world with clear digital audio. It combines a custom-designed PCB, a 3D-printed enclosure, and simple controls to create an easy-to-use internet radio for your desk or workspace.

The project is built around the **ESP32-S3**, which manages the Wi-Fi connection, downloads the audio stream from the internet, decodes it, and sends digital audio to the **MAX98357 I2S amplifier**. The amplifier directly drives a **4Ω speaker** for clean and efficient sound. A **0.96-inch OLED display** shows useful information such as the current station and connection status, while a **rotary encoder** allows you to switch between saved stations and adjust the volume.

The PCB was designed in **EasyEDA Pro** to make the project compact and eliminate unnecessary wiring. A custom enclosure was created in **Fusion 360** and 3D printed using PLA, resulting in a clean desktop design that securely holds all of the components.

---

# Features

- ESP32-S3 Wi-Fi Microcontroller
- Internet Radio Streaming
- MAX98357A I2S Digital Audio Amplifier
- 0.96" I2C OLED Display
- Rotary Encoder for Navigation
- Custom EasyEDA PCB
- Compact 3D Printed Enclosure
- 5V DC Power Input
- Clean and Modular Design

---

# Project Images

## Schematic

<p align="center">
  <img src="images/schematic.png" width="850">
</p>

---

## PCB Layout

<p align="center">
  <img src="images/pcb_layout.png" width="850">
</p>

---

## 3D PCB View

<p align="center">
  <img src="images/pcb_3d.png" width="750">
</p>

---

## Manufactured PCB

<p align="center">
  <img src="images/pcb_real.jpg" width="750">
</p>

---

## 3D Printed Enclosure

<p align="center">
  <img src="images/enclosure.png" width="750">
</p>

---

## Final Assembly

<p align="center">
  <img src="images/final_assembly.jpg" width="750">
</p>

---

# Bill of Materials (BOM)

| Qty | Component |
|:---:|-----------|
| 1 | ESP32-S3 Development Board |
| 1 | MAX98357A I2S Audio Amplifier |
| 1 | 0.96" OLED Display (I2C) |
| 1 | Rotary Encoder |
| 1 | 4Ω Speaker |
| 1 | DC Barrel Jack |
| 1 | 2-Pin Screw Terminal |
| 3 | 2.54 mm Pin Headers |
| 1 | Custom PCB |

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

The firmware was developed using the **Arduino Framework** for the ESP32-S3. After powering on, the device automatically connects to the configured Wi-Fi network and starts streaming one of the predefined internet radio stations. Additional stations can easily be added by modifying the source code.

---

# Tools Used

- EasyEDA Pro
- Arduino IDE
- Fusion 360
- JLCPCB
- 3D Printer

---

# License

This project is open-source and intended for learning, educational purposes, and personal projects. Feel free to modify, improve, and build upon the design.
