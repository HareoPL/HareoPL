# 👋 Hi, I'm Jan Łukaszewicz

### Embedded Engineer | Hardware Diagnostics Expert | Cybersecurity Enthusiast

I am currently working as an embedded engineer, combining software development with a strong, 16-year background in component-level electronics diagnostics (BGA/SMD). Because of this, I perfectly understand how hardware works – I can read schematics, use an oscilloscope or a logic analyzer, and seamlessly transfer this knowledge into the software layer.

I can complete the entire project cycle: from designing a custom PCB, through writing efficient firmware, to designing a graphical user interface in TouchGFX. On a daily basis, I write code in **Embedded C**, utilizing **FreeRTOS** on **STM32** and **ESP32** architectures.

I am currently a student specializing in Cybersecurity, and my main goal is to create reliable and secure embedded systems. I am particularly interested in IoT network security and Secure Boot.

📫 **Contact & Links:**

* 💼 **LinkedIn:** [linkedin.com/in/jan-luk](https://linkedin.com/in/jan-luk)
* 🌐 **Portfolio/Documentation:** [hareo.pl/otapp](https://hareo.pl/otapp)
* 📧 **Email:** [jlukjob@gmail.com]()

---

## 🛠️ Technical Skills

* **Languages & Systems:** Embedded C (Bare Metal/HAL), FreeRTOS
* **Microcontrollers:** STM32 (Cortex-M), ESP32
* **Protocols & Connectivity:** OpenThread, MQTT (3.1.1), CoAP, Modbus-RTU, CAN, SPI, I2C, UART
* **Tools:** ESP-IDF, STM32CubeIDE, TouchGFX, Git, Unity, FFF
* **Hardware:** Fault diagnostics, BGA/SMD soldering, laboratory equipment operation

---

## 🚀 Main Projects

Most of my public repositories make up my flagship, comprehensive IoT ecosystem based on the **OpenThread** protocol. It has been divided into clear modules depending on the architecture and function within the distributed control network.

### 🌐 OpenThread IoT Ecosystem (OTApp)

An application layer (middleware) I designed that allows devices to automatically discover each other, pair, and communicate asynchronously.

* 📦 **[ot_app](https://github.com/HareoPL/ot_app)** — The main framework and core of the ecosystem. It contains universal system logic and an abstraction layer managing network events, independent of any specific microcontroller.
* 🟢 **[ot_app_esp](https://github.com/HareoPL/ot_app_esp)** — A port of the OTApp ecosystem implemented for the ESP32 microcontroller family (including ESP32-C6).
* 🔵 **[ot_app_stm](https://github.com/HareoPL/ot_app_stm)** — A port of the OTApp ecosystem optimized for the STM32 platform (e.g., STM32WBA65RI utilizing hardware GPDMA).
* 🖥️ **[ot_app_cp](https://github.com/HareoPL/ot_app_cp)** — Control Panel (HMI). A repository containing the code for an advanced graphical user interface designed in TouchGFX. It utilizes DMA2D hardware acceleration on a powerful STM32H7 microcontroller.
* 🛜 **[ot_app_br](https://github.com/HareoPL/ot_app_br)** — Border Router implementation, serving as an access gateway connecting the OpenThread Mesh network with an external Wi-Fi/IP network.

*I am currently expanding this ecosystem with an MQTT gateway connected to an LTE modem, which will collect data from the sensor network and send it to the cloud for analysis.*

### 🛠️ Hardware Design & PCB

* 🔌 **[ESP-CAN-RF](https://github.com/HareoPL/ESP-CAN-RF)** — A fully custom printed circuit board (PCB) design. The repository represents a complete project cycle integrating the ESP32 microcontroller with nRF radio modules and a CAN bus interface. The board was designed, assembled, and programmed from scratch.
