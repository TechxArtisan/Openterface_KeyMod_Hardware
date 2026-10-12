# Welcome to Openterface_KeyMod_Hardware

<img width="3072" height="3069" alt="ppt5" src="https://github.com/user-attachments/assets/11335c8d-30f8-44c0-8233-cd70c9037e02" />


## Overview

The [Openterface KeyMod](https://openterface.com/keymod/) is a compact and portable open-source USB control gadget designed to turn your smartphone into a keyboard and mouse for a target device.

The KeyMod series includes two hardware variants, designed for different USB interfaces:

- KeyMod Mini: USB-C connector, with Bluetooth LE phone connectivity.
- KeyMod Plus: USB-A connector, with Bluetooth LE or wired USB phone connectivity.

Each variant provides hardware-based keyboard and mouse emulation. By connecting KeyMod to the target machine's USB port, users can control the system through the KeyCmd app without requiring Wi-Fi or additional software on the target.

This solution is particularly useful for developers, IT professionals, and hardware enthusiasts who work with computers, servers, Raspberry Pi boards, kiosks, and other USB-enabled devices.

## Hardware Features

The Openterface KeyMod PCB board comes with a variety of features designed to provide a seamless and efficient user experience:

- Compact Design: Small and portable form factor suitable for everyday carry.
- Multiple USB Variants: Available in USB-C and USB-A versions to support different target devices.
- Bluetooth Connectivity: Connects your smartphone to KeyMod for wireless control.
- Wired Connectivity: KeyMod Plus supports a wired USB connection to the controlling phone.
- USB HID Control: Emulates standard keyboard and mouse inputs, including in compatible BIOS/UEFI environments.
- USB Powered: Powered by the target device, with no battery required.
- Open Source: Hardware and software source materials are being published as the project evolves.
- [Community Support](https://forum.openterface.com/): Backed by an active open-source community.

<img width="3229" height="1818" alt="keym&#39;1" src="https://github.com/user-attachments/assets/c792baea-ff81-4756-aeda-0b41dff2ca02" />


## Firmware

KeyMod works with [Openterface_KM](https://github.com/TechxArtisanStudio/Openterface_KM), the keyboard and mouse emulation firmware used for target-side HID control in the Openterface ecosystem.

## Software

To use KeyMod, install the [KeyCmd app](https://openterface.com/keycmd/) on your smartphone.

Supported platforms include:

- [iOS](https://apps.apple.com/us/app/keycmd/id6776206628)
- [Android](https://openterface.com/keycmd/)

KeyCmd provides keyboard, touchpad, numpad, KM Pro, Compose & Send, presentation, gamepad, macro, and Terminal modes. Gamepad controls are mapped to standard keyboard and mouse input.

No additional software installation is required on the target for keyboard and mouse control. Simply connect KeyMod to a USB port that supports USB HID devices.

Terminal mode provides SSH access through KeyMod's network bridge on supported macOS and Linux targets, with an SSH service enabled.

<img width="3092" height="3092" alt="ppt1" src="https://github.com/user-attachments/assets/69a24af5-e46e-48f9-a80d-9577b8feff20" />


## PCB Design

<img width="1280" height="720" alt="pcb-layout" src="https://github.com/user-attachments/assets/c4295b7b-f76b-4b83-bfa8-a0f4d921e080" />


## license

- Hardware is released under CERN Open Hardware Licence Version 2 - Strongly Reciprocal
- Its softwares are released under GNU AFFERO GENERAL PUBLIC LICENSE Version 3
- Documentation is released under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode)

## Get Involved

Interested in contributing to the project? We welcome community involvement and contributions. For more information about getting involved, please visit the [Openterface Forum](https://forum.openterface.com/) or contact us directly.
