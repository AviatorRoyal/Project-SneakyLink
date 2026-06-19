# Project SneakyLink

> **Communication Beyond Coverage.**

![License](https://img.shields.io/badge/License-GPLv3-blue.svg)
![Status](https://img.shields.io/badge/Status-Active%20Development-orange)
![Hardware](https://img.shields.io/badge/MCU-ESP32--S3-green)
![Radio](https://img.shields.io/badge/Radio-nRF24L01%2B-red)
![Designed With](https://img.shields.io/badge/Designed%20With-EasyEDA-blueviolet)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-brightgreen)

---

![PCB Top](https://github.com/AviatorRoyal/Project-SneakyLink/blob/main/harware/pcb/RevA/Images/Top.png)

![PCB Bottom](https://github.com/AviatorRoyal/Project-SneakyLink/blob/main/harware/pcb/RevA/Images/Bottom.png)

---

## Overview

**Project SneakyLink** is an open-source hardware and firmware platform for secure, portable, off-grid text communication.

Designed around the **ESP32-S3** and **nRF24L01+** radio transceiver, SneakyLink enables medium-range communication without relying on cellular networks, Wi-Fi, or internet infrastructure.

The project is intended to serve as both a practical communication device and a platform for experimenting with embedded systems, wireless networking, RF protocols, and secure communications.

---

## Motivation

Reliable communication should not depend entirely on existing infrastructure.

Whether you're exploring remote areas, responding to emergencies, learning embedded systems, or simply experimenting with wireless communication, SneakyLink aims to provide a portable, open-source platform capable of operating independently of conventional networks.

---

## Current Hardware

| Component | Description |
|-----------|-------------|
| MCU | ESP32-S3-WROOM-1 |
| Radio | nRF24L01+ |
| External Flash | W25Q128 (16 MB SPI Flash) |
| Display | I²C OLED Display |
| Charging | USB Type-C |
| Battery Management | Power Path Charging |
| User Input | Navigation Buttons |
| Feedback | Buzzer & Vibration Motor |
| Expansion | Exposed UART Header |

---

## Planned Features

### Messaging

- Secure text messaging
- Private device-to-device communication
- Message history
- Delivery acknowledgement (ACK)
- Store-and-forward messaging for temporarily unavailable devices

### Communication

- Frequency Hopping Spread Spectrum (FHSS)
- End-to-end encryption
- Reliable packet handling
- Device pairing

### User Experience

- OLED-based interface
- Device configuration
- Contact management
- Battery monitoring

### Entertainment

- Single-player games
- Multiplayer games over radio

---

## Roadmap

### Revision A

- [x] Hardware design
- [x] PCB layout
- [x] USB-C charging
- [x] OLED support
- [x] External Flash
- [x] nRF24L01+ integration
- [ ] Firmware development
- [ ] Basic messaging
- [ ] Encryption
- [ ] FHSS

### Future Revisions

- [ ] LoRa support
- [ ] Mesh networking
- [ ] OTA firmware updates over Wi-Fi
- [ ] Companion desktop application
- [ ] Companion mobile application
- [ ] Improved power optimization

---

## Repository Structure

```text
hardware/    PCB design files and fabrication outputs
firmware/    ESP32 firmware
docs/        Project documentation
```

---

## Technologies

- ESP32-S3
- nRF24L01+
- EasyEDA
- C / C++
- Embedded Systems
- RF Communication

---

## Project Status

> **Active Development**

Hardware Revision A has been completed.

Firmware development is currently underway, with secure messaging forming the primary milestone for the first public release.

---

## Contributing

Contributions are welcome.

Whether you're interested in firmware development, PCB design, RF communication, documentation, testing, or feature ideas, feel free to open an Issue or submit a Pull Request.

---

## License

This project is licensed under the **GNU General Public License v3.0 (GPL-3.0)**.

See the [LICENSE](LICENSE) file for details.
