# STM32 B-L475E-IOT01A Firmware Portfolio

This repository aggregates a structured series of embedded firmware
projects developed on the STM32 B-L475E-IOT01A Discovery board.

The portfolio demonstrates progressive firmware development concepts
including GPIO control, interrupt handling, UART logging, and I²C
sensor drivers.

---

## Hardware Platform
- Board: STM32 B-L475E-IOT01A
- MCU: STM32L475VGT6 (Cortex-M4F)
- Interfaces Used:
  - GPIO
  - EXTI
  - USART1 (PB6/PB7)
  - I²C1 (PB8/PB9)

---

## Project List

### 1. GPIO Output Driver  
Repository:  
https://github.com/BOSSX918spy/stm32-bl475eiot1a1-gpio-output-driver

Focus:
- GPIO configuration
- Clock setup
- HAL timing model

---

### 2. GPIO Button Interrupt with Debounce  
Repository:  
https://github.com/BOSSX918spy/stm32-bl475eiot1a1-gpio-button-interrupt

Focus:
- EXTI interrupts
- ISR best practices
- Software debounce strategy

---

### 3. UART Debug Console  
Repository:  
https://github.com/BOSSX918spy/stm32-bl475eiot1a1-uart-debug-console

Focus:
- UART abstraction layer
- Formatted logging
- Debug architecture

---

### 4. HTS221 I²C Sensor Driver  
Repository:  
https://github.com/BOSSX918spy/stm32-bl475eiot1a1-i2c-hts221-driver

Focus:
- Sensor abstraction
- BSP integration
- Floating-point handling

---

### 5. LPS22HB Pressure Sensor Driver  
Repository:  
https://github.com/BOSSX918spy/stm32-bl475eiot1a1-i2c-lps22hb-driver

Focus:
- Multi-sensor I²C bus
- Driver layering
- Environmental telemetry

---

## Architecture Philosophy

All projects follow a layered firmware model:

Application → Driver → BSP → HAL → Hardware

This mirrors production embedded system design practices.


---

## Development Context

These firmware projects were developed at the **IoT Innovation Lab**,  
Department of Electronics and Communication Engineering,  
**Chitkara University**.

The work was completed as part of hands-on embedded systems learning
and practical experimentation on real hardware platforms.

---

## Acknowledgements

I would like to express my sincere gratitude to:

- **Dr. Amit Kumar**
- **Dr. Amarjeet Kaur**
- **Mr. Rakesh Kumar**

for their guidance, mentorship, and support throughout the development
of these projects.

