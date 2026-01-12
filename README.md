# Embedded Systems Design: Coffee Maker Case Study (MCT 425)

A compact, end-to-end embedded systems case study using a **modern coffee maker** to demonstrate real-time firmware design, control algorithms, and safety-critical thinking.

This repository contains a **print-ready technical report** developed for **MCT 425 – Embedded Systems** at the **Air Force Institute of Technology (AFIT)**, Department of Mechatronics Engineering.

---

## Why This Project

Coffee makers are deceptively complex cyber-physical systems. Behind a simple button press lies:

* millisecond-level timing constraints,
* closed-loop temperature control,
* interrupt-driven sensing, and
* layered safety mechanisms.

This project isolates and explains that digital intelligence—**the embedded system itself**.

---

## What’s Inside

The report walks through the complete embedded stack:

* **MCU Architecture** – ATmega328P selection, memory map, and peripherals
* **Firmware Design** – Finite State Machine (FSM)–driven logic
* **Real-Time Operation** – timers, interrupts, and deadline analysis
* **Control Systems** – PID temperature control and volumetric dispensing
* **I/O Interfacing** – ADC sensing, PWM actuation, electrical isolation
* **Safety & Reliability** – watchdog timers, interlocks, hardware fail-safes

All concepts are grounded in a realistic appliance-scale system rather than abstract examples.

---

## Key Ideas Demonstrated

* Deterministic **FSM-based firmware architecture**
* **Interrupt-first design** for accurate measurement
* Precision **PID control** on a resource-constrained MCU
* Meeting real-time deadlines **without an RTOS**
* Multi-layer safety in embedded consumer products

---

## Repository Structure

```
report.html   # Main report (styled, print-ready HTML)
afit_logo.png      # Optional background watermark asset
README.md           # Project overview
```

The HTML document supports on-screen viewing and clean **A4 printing**, with diagrams, equations (MathJax), and annotated code snippets.

---

## How to View

1. Clone or download the repository
2. Open `report.html` in any modern browser
3. (Optional) Print to PDF using A4 settings for best layout

---

## Academic Context

* **Course:** MCT 425 – Embedded Systems
* **Institution:** Air Force Institute of Technology (AFIT)
* **Department:** Mechatronics Engineering
* **Session:** 2025/2026

Produced as a formal academic submission. 
---

## Intended Audience

* Embedded systems and firmware students
* Mechatronics / electrical engineering undergraduates
* Instructors teaching control and real-time systems
* Readers looking for a concrete, end-to-end embedded example

---

## License

Provided for **educational and academic reference**. Attribution is expected for reuse.

---

**Concise system. Predictable behavior. Real coffee.**
