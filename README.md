# 👋 Hi, I'm Jan Łukaszewicz

### Hardware Whisperer (Embedded Engineer / Diagnostics Expert / Creator) 🇵🇱 Ząbki, Poland

I am a embedded engineer combining modern software development with a hardcore background in component-level electronics diagnostics (BGA/SMD). Because of this, I perfectly understand how hardware works under the hood. I don't just write code; I read schematics, hook up logic analyzers, and seamlessly transfer low-level hardware behavior into the software abstraction layer.

I handle the entire project lifecycle: from designing custom PCBs, through writing efficient bare-metal/RTOS firmware, to designing beautiful graphical user interfaces in TouchGFX.

---

### 👨‍💻 About Me & What I Do

- 💼 **Professional Background:** I bring over 15 years of hands-on experience in component-level electronics diagnostics to the table. My expertise includes extensive hardware reverse-engineering, low-level BIOS/KBC programming, advanced BGA/SMD repairs, and signal analysis using laboratory equipment.
- 🎓 Currently studying **Informatics with a specialization in Cybersecurity** at Uniwersytet Vizja in Warsaw (Expected 2028). My main focus is creating reliable, hardened embedded systems, IoT network security, and Secure Boot implementations.
- 🚀 Active participant in the embedded ecosystem. You might have caught me at events like the **Droniada Future Forum 2025** or multiple iterations of the **STM32 Masters** workshops.
- ⚙️ Deeply passionate about the reverse engineering of microcontrollers and mechanical systems.
- 🚴‍♂️ When I am away from my soldering station and debugger, I spend my time swimming, terrain cycling, and enjoying life with my wife Ewa, our daughter, and our dog, Snapi.

📫 **Contact & Links:**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jan-luk)
[![Portfolio](https://img.shields.io/badge/Portfolio-252525?style=for-the-badge&logo=google-chrome&logoColor=white)](https://hareo.pl/otapp)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jlukjob@gmail.com)

---

### 🛠️ Tech Stack & Tools

**Core Languages & OS:**
![C](https://img.shields.io/badge/Embedded_C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-20232A?style=for-the-badge&logo=freertos&logoColor=white)

**Microcontrollers & Architectures:**
![STM32](https://img.shields.io/badge/STM32_(Cortex--M)-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)

**Connectivity & Protocols:**
![OpenThread](https://img.shields.io/badge/OpenThread-4B8B3B?style=for-the-badge)
![MQTT](https://img.shields.io/badge/MQTT_3.1.1-660066?style=for-the-badge&logo=mqtt&logoColor=white)
![CAN Bus](https://img.shields.io/badge/CAN_Bus-005571?style=for-the-badge)
![CoAP](https://img.shields.io/badge/CoAP-25A162?style=for-the-badge)
![Modbus](https://img.shields.io/badge/Modbus_RTU-007ACC?style=for-the-badge)

**Tools & Workflows:**
![STM32CubeIDE](https://img.shields.io/badge/STM32CubeIDE-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![ESP-IDF](https://img.shields.io/badge/ESP--IDF-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![TouchGFX](https://img.shields.io/badge/TouchGFX-4B8B3B?style=for-the-badge)

---

### 🚀 Flagship Projects

Most of my public repositories make up my comprehensive IoT ecosystem based on the **OpenThread** protocol. It is divided into clear modules depending on the architecture and function within the distributed control network.

#### 🌐 OpenThread IoT Ecosystem (OTApp)
An application layer (middleware) I designed that allows devices to automatically discover each other, pair, and communicate asynchronously.

* 📦 **[ot_app](https://github.com/HareoPL/ot_app/tree/feature/ot_app/mqtt-gsm-gateway)** — The main framework and core of the ecosystem. It contains universal system logic and an abstraction layer managing network events and messaging (utilizing `ot_app_msg_tlv` for serialization), making it entirely independent of any specific microcontroller.
* 🟢 **[ot_app_esp](https://github.com/HareoPL/ot_app_esp)** — A port of the OTApp ecosystem implemented for the ESP32 microcontroller family (including ESP32-C6).
* 🔵 **[ot_app_stm](https://github.com/HareoPL/ot_app_stm)** — A port of the OTApp ecosystem optimized for the STM32 platform (e.g., STM32WBA65RI utilizing hardware GPDMA).
* 🖥️ **[ot_app_cp](https://github.com/HareoPL/ot_app_cp/tree/otapp_cp)** — Control Panel (HMI). Advanced graphical user interface designed in TouchGFX, utilizing DMA2D hardware acceleration on a powerful STM32H7 microcontroller.
* 🛜 **[ot_app_br](https://github.com/HareoPL/ot_app_br)** — Border Router implementation, serving as an access gateway connecting the OpenThread Mesh network with an external Wi-Fi/IP network.

> *I am currently expanding this ecosystem with an MQTT gateway connected to an GSM modem to collect data from the sensor network and push it directly to the cloud for analysis.*

#### 🛠️ Hardware Design & PCB
* 🔌 **[ESP-CAN-RF](https://github.com/HareoPL/ESP-CAN-RF)** — A fully custom two-layer printed circuit board (PCB) design. This repository represents a complete project cycle integrating the ESP32 with nRF24L01+ radio modules, a SIM800L modem, and a CAN bus interface. It features a custom 230V SSR design with VOM1271T/TLP250 galvanic isolation. Designed, assembled, and programmed entirely from scratch.

---

### 📚 Continuous Learning
I am dedicated to expanding my embedded software and hardware design expertise. My notable training includes:
* **InterTechAcademy:** Real-Time Operating Systems (RTOS), ARM Cortex-M architecture, and PCB / Electronic Circuit Design.
* **ucgosu.pl:** Test-Driven Development (TDD) in Embedded Systems, Advanced C, and Git version control.
* **msalamon.pl:** STM32 register-level programming and C for microcontrollers.

---
<!--
### 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=HareoPL&show_icons=true&theme=tokyonight" alt="Jan's GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=HareoPL&theme=tokyonight" alt="Jan's GitHub Streak" />
</div>
-->
