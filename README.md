# ⚠️ Honest Notes About This PCB (v1.0)

> 🫧🫧🫧

**Yes… the PCB layout is pretty bad.**
I know it. You know it. We all know it. 🫠

I intentionally forced **all SMD components to the bottom side** while keeping the microcontroller and its surrounding parts on the top side.
This decision caused a massive increase in via count and introduced a lot of small (and some not-so-small) design issues.

This is just the **first prototype**.
A much cleaner **PCB Version 2** is already planned.

Thanks for understanding! 🛠️❤️

> 🫧🫧🫧

---

## 📦 Bill of Materials (BOM)

| Designator | Part / Value | Description | Qty | Notes |
|---|---|---|---|---|
| U1 | STM32F103C8T6 | ARM Cortex-M3 MCU, 64KB Flash, LQFP-48 | 1 | Main microcontroller |
| U2 | CH340N | USB to UART converter | 1 | USB serial interface |
| U4 | AMS1117-3.3 | 3.3V LDO Regulator | 1 | Power supply |
| USB1 | USB Type-C 16-Pin | USB Type-C Connector | 1 | Power / Data |
| USB2 | USB Type-C 16-Pin | USB Type-C Connector | 1 | Power / Data |
| PA1 | Header 2×8 | 16-pin Dual Row Header | 1 | GPIO Port A |
| PA2 | Header 2×8 | 16-pin Dual Row Header | 1 | GPIO Port A |
| PB1 | Header 2×8 | 16-pin Dual Row Header | 1 | GPIO Port B |
| PB2 | Header 2×8 | 16-pin Dual Row Header | 1 | GPIO Port B |
| P1 | Header 1×5 | 5-pin Single Row Header | 1 | Extra I/O |
| P2 | Header 1×5 | 5-pin Single Row Header | 1 | Extra I/O |
| HD49-8MHz | 8 MHz Crystal | Main system clock | 1 | HSE |
| 32.768KHz | 32.768 kHz Crystal | RTC clock | 1 | LSE |
| C1 | 18 pF | Ceramic Capacitor | 1 | Crystal load |
| C2 | 18 pF | Ceramic Capacitor | 1 | Crystal load |
| C3 | 100 µF | Electrolytic Capacitor | 1 | Power decoupling |
| C4 | 100 µF | Electrolytic Capacitor | 1 | Power decoupling |
| C5 | 100 nF | Ceramic Capacitor | 1 | Decoupling |
| C6 | 100 nF | Ceramic Capacitor | 1 | Decoupling |
| R1 | 220 Ω | Resistor | 1 | LED current limit |
| R3 | 220 Ω | Resistor | 1 | LED current limit |
| R5 | 220 Ω | Resistor | 1 | LED current limit |
| R2 | 5.1 kΩ | Resistor | 1 | USB CC / Pull-up |
| R4 | 5.1 kΩ | Resistor | 1 | USB CC / Pull-up |
| R6 | 5.1 kΩ | Resistor | 1 | USB CC / Pull-up |
| R7 | 5.1 kΩ | Resistor | 1 | USB CC / Pull-up |
| R8 | 10 kΩ | Resistor | 1 | Pull-up / Pull-down |
| R9 | 10 kΩ | Resistor | 1 | Pull-up / Pull-down |
| D1 | LED | Status / Power LED | 1 | - |
| D2 | LED | Status LED | 1 | - |
| D3 | LED | Status LED | 1 | - |
| B1 | Push Button 4-Pin | Tactile Switch | 1 | User / Reset button |
| S1 | SW DIP-1 | 1-position DIP Switch | 1 | Configuration |
