# 🚀 STM32F401 Custom Development Board Design

## 📌 Overview

This project presents the design of a custom **STM32F401-based development board** using KiCad.
It focuses on creating a reliable hardware platform for embedded system applications by integrating power supply, communication interfaces, and debugging support.

---

## 🎯 Objective

To design a compact and efficient STM32F401 development board with essential peripherals and proper PCB layout techniques.

---

## ⚙️ Design Features

* STM32F401 (ARM Cortex-M4) microcontroller
* USB interface for communication
* USART (Serial Communication) header
* I2C interface support
* SWD (Serial Wire Debug) interface
* 3.3V regulated power supply
* Decoupling capacitors for stable operation

---

## 🧠 Design Considerations

* Proper placement of decoupling capacitors near VDD pins
* Ground plane used to reduce electrical noise
* Optimized trace routing for signal integrity
* Separation of power and signal sections
* Compact and efficient component placement

---

## 📂 Project Structure

* `/docs` → Schematic and PCB images
* `/src` → (Future firmware development)
* `README.md` → Project documentation

---

## 📸 Hardware Design

### 🔹 Schematic

![Schematic](docs/stm32_schematic.png)

### 🔹 PCB Layout

![PCB](docs/stm32_pcb_layout.png)

---

## 🛠️ Tools Used

* KiCad (PCB Design Software)
* Embedded Systems Design Principles

---

## 🚀 Future Work

* PCB fabrication and assembly
* Firmware development using Embedded C
* Peripheral driver implementation (UART, SPI, I2C)
* Testing and debugging on hardware

---

## 📌 Note

This project focuses on **hardware design and PCB layout**.
Physical fabrication and testing are planned as future work.

---

## 💡 Key Learning Outcomes

* STM32 microcontroller hardware design
* PCB layout and routing techniques
* Power management in embedded systems
* Interface design (USART, I2C, SWD)

---

## 🔗 Author

**Atharv Dhoke**
