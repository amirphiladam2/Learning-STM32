# Learning STM32 🚀

Welcome to my STM32 learning journey! This repository documents my progress, projects, and experiments as I dive into the world of ARM Cortex-M microcontrollers using STM32.

## 🛠 Hardware & Tools

- **Microcontroller**: STM32F411RE (Nucleo-64)
- **IDE**: STM32CubeIDE
- **Firmware Package**: STM32CubeF4

## 📂 Project Structure

| Project Folder | Description | Key Concepts |
| :--- | :--- | :--- |
| **BLINKLED** | The "Hello World" of embedded systems. Toggles an onboard LED. | GPIO Output, HAL Delay, Project Setup |
| **GPIO** | Experiments with General Purpose Input/Output. | GPIO Input (Button), GPIO Output, Pull-up/Pull-down |

## 🚀 How to Run

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/amirphiladam2/Learning-STM32.git
    ```
2.  Open **STM32CubeIDE**.
3.  Select **File > Open Projects from File System...**
4.  Navigate to the `BLINKLED` or `GPIO` directory and click **Finish**.
5.  Build (Hammer icon) and Debug/Run (Bug/Play icon).

## 📝 Notes

- Code is generated using STM32CubeMX and then modified in `main.c`.
- Focus is on understanding the HAL (Hardware Abstraction Layer) and eventually Low-Layer (LL) drivers.

---
*Documenting my journey to master Embedded Systems.*
