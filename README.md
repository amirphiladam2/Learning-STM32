# Learning STM32 

Welcome to my STM32 learning journey! This repository documents my progress, projects, and experiments as I dive into the world of ARM Cortex-M microcontrollers using STM32.

## 🛠 Hardware & Tools

- **Microcontroller**: STM32F411RE (Nucleo-64)
- **IDE**: STM32CubeIDE
- **Firmware Package**: STM32CubeF4

##  How to Run

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/amirphiladam2/Learning-STM32.git
    ```
2.  Open **STM32CubeIDE**.
3.  Select **File > Open Projects from File System...**
4.  Navigate to the `BLINKLED` or `GPIO` directory and click **Finish**.
5.  Build (Hammer icon) and Debug/Run (Bug/Play icon).


## 🗺️ Roadmap

### 🔹 PHASE 1 — Core Microcontroller Control
- [x] Clock Configuration (RCC)
- [x] GPIO (Input / Output / Pull-up / Pull-down) *(Covered in BLINKLED & GPIO)*
- [x] EXTI (External Interrupts)
- [ ] Basic Timer (Interrupt mode)
- [ ] PWM Generation
- [ ] Input Capture (Timer)

### 🔹 PHASE 2 — Communication Protocols
- [ ] UART (Polling mode)
- [ ] UART (Interrupt mode)
- [ ] UART with printf Redirection
- [ ] I2C Master Mode
- [ ] SPI Master Mode
- [ ] I2C Sensor Interfacing
- [ ] SPI Device Interfacing

### 🔹 PHASE 3 — Analog & Data Movement
- [ ] ADC (Single Channel)
- [ ] ADC Continuous Mode
- [ ] ADC with Interrupt
- [ ] ADC with DMA
- [ ] UART with DMA

### 🔹 PHASE 4 — System-Level Understanding
- [ ] Memory Map Study (Flash, SRAM, Peripheral region)
- [ ] Stack vs Heap
- [ ] Vector Table
- [ ] NVIC Configuration
- [ ] Low Power Modes
- [ ] Watchdog Timer (IWDG / WWDG)

### 🔹 PHASE 5 — RTOS
- [ ] FreeRTOS Basics
- [ ] Tasks
- [ ] Queues
- [ ] Semaphores / Mutex
- [ ] Task Scheduling Concepts

### 🔹 PHASE 6 — Bare Metal (Register Level)
- [ ] GPIO Using Registers
- [ ] Timer Using Registers
- [ ] UART Using Registers
- [ ] Clock Configuration Using Registers
- [ ] Interrupt Setup Using Registers

###    Optional (Advanced Tier)
- [ ] Bootloader Basics
- [ ] CMSIS Understanding
- [ ] Custom Peripheral Driver Creation
- [ ] Linker Script Basics
- [ ] Memory Section (.text, .data, .bss)
- [ ] Power Optimization Techniques

## 📝 Notes

- Code is generated using STM32CubeMX and then modified in `main.c`.
- Focus is on understanding the HAL (Hardware Abstraction Layer) and eventually Low-Layer (LL) drivers.

---
*Documenting my journey to master Embedded Systems.*
