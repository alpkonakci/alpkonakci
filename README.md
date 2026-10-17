# Ömer Alp Konakcı

### Embedded Systems · PCB Design · Practical Software

I'm an Electrical & Electronics Engineer. I work across STM32 firmware, custom electronics, and software that connects devices to useful applications.

My engineering background includes modular industrial control, CAN communication, motor drivers, and UAV avionics. I enjoy taking projects from circuit and code to something people can actually use.

[LinkedIn](https://www.linkedin.com/in/omeralpkonakci/)

---

## Currently building

### [Webcam QR Scanner](https://github.com/alpkonakci/webcam-qr-scanner)

A Windows application for reading QR codes from a camera or directly from the screen, with a phone-to-PC workflow in development.

- **Desktop:** camera and screen scanning, responsive background decoding, and a standalone Windows download.
- **Phone-to-PC beta:** mobile web app, device pairing, and encrypted link delivery with confirmation on the PC.
- **Current focus:** clearer connection states, accessibility, and a smoother mobile-to-desktop experience.

The desktop release and the phone-to-PC beta are documented separately; the beta is still undergoing validation.

[Source code](https://github.com/alpkonakci/webcam-qr-scanner) · [Demo](https://github.com/alpkonakci/webcam-qr-scanner#demo) · [Downloads & release notes](https://github.com/alpkonakci/webcam-qr-scanner/releases)

`Python` · `OpenCV` · `Windows` · `TypeScript` · `Next.js` · `WebCrypto`

---

## Featured engineering project

### MCT-APEX — Modular Industrial Controller

My graduation project connects STM32-based motor and sensor modules through CAN, with a UART bridge to a Raspberry Pi 5. It brings together PCB design, embedded firmware, and system integration.

```text
Raspberry Pi 5
      ↕ UART
STM32 bridge
      ↕ CAN
Motor control + Sensor modules
```

- **[Thesis firmware](https://github.com/alpkonakci/mct-stm32-thesis-firmware):** non-RTOS STM32 HAL implementation with a DRV8876 motor node, sensor node, and UART–CAN bridge.
- **[FreeRTOS firmware](https://github.com/alpkonakci/mct-stm32-freertos):** task-based implementation separating control, communication, telemetry, and fault handling.

`C` · `STM32` · `FreeRTOS` · `CAN Bus` · `UART` · `PWM` · `KiCad`

---

## Engineering stack

| Area | Tools & technologies |
| --- | --- |
| Embedded | C / C++, STM32, ARM Cortex, HAL, FreeRTOS |
| Hardware | KiCad, Altium Designer, analog circuits, motor drivers |
| Communication | CAN bus, Modbus, UART, TCP/IP |
| Software | Python, C#, OpenCV; TypeScript / Next.js in the QR project |
| Simulation | MATLAB / Simulink, ANSYS Maxwell |

## Beyond the repositories

At PAÜ İstikbal's Teknofest UAV team, I worked on IMU/GNSS sensor fusion, data transmission, and avionics integration. Internships at Vestel Elektronik and Kale Seramik gave me experience with production validation and mechanical–electrical integration.

I'm interested in real-time control, reliable device communication, and building hardware and software that work well together.

## Contact

[LinkedIn](https://www.linkedin.com/in/omeralpkonakci/)
