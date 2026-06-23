# Hakputer Pro CM5

**Concept:** Portable Cyberdeck + Field Operations Terminal  
**Status:** Fictional product concept / design specification  
**Positioning:** A rugged CM5-powered handheld Linux cyberdeck combining M5Stack-style modular maker hardware with Hak5-style cybersecurity workflows.

> This is an unofficial concept description. It is not an official M5Stack, Hak5, Raspberry Pi, or Cloud C² product.

---

## 1. Concept Summary

The **Hakputer Pro CM5** is a fictional portable cyberdeck and field operations terminal imagined as a collaboration-style device inspired by the build philosophies of **M5Stack** and **Hak5**.

It is designed as a rugged handheld Linux computer built around a **Raspberry Pi Compute Module 5-class core**, intended for authorized cybersecurity work, device management, IoT development, field diagnostics, training, and portable infrastructure control.

It is not just a small computer. It is intended to act as a **central command console** for connected hardware, sensors, security tools, modules, and cloud-managed devices.

The concept combines:

- **M5Stack-style design:** compact, modular, maker-friendly, clearly labeled, expansion-focused, sensor-compatible, and easy to prototype with.
- **Hak5-style design:** stealthy, rugged, field-ready, security-focused, payload-aware, professional, and built around cybersecurity workflows.

The final identity should feel like a serious **maker-security field computer**, not a toy and not simply a laptop replacement.

---

## 2. One-Sentence Description

The **Hakputer Pro CM5** is a rugged CM5-powered handheld Linux cyberdeck that blends M5Stack-style modular maker hardware with Hak5-style cybersecurity workflows, using internal storage for the OS and a swappable full-size SSD cartridge as the primary data drive for field work, labs, modules, and authorized security projects.

---

## 3. Physical Design

The device would look like a rugged handheld cyberdeck with a wide rectangular body, a built-in display, a compact keyboard, visible ports, expansion connectors, and a removable SSD bay.

The body would use a **dark matte black outer shell** with **gray or gunmetal inner panels**. The outer case should feel closer to Hak5: tactical, stealthy, angular, and field-tool-like. The inner faceplate and visible I/O zones should feel closer to M5Stack: clean, organized, modular, clearly labeled, and builder-friendly.

### Physical features

- 4.5- to 5-inch touchscreen
- Compact QWERTY keyboard
- Function keys
- Directional keys
- Status LEDs
- Hardware buttons
- Visible screws
- Rubberized corner protection
- Cooling vents
- Orange/yellow accent strips
- Clearly labeled I/O zones
- Sturdy bottom accessory SSD bay
- Docking contacts on the bottom or rear
- Rear service/access panel

The device should look like something between a **portable Linux terminal**, a **field radio/data console**, a **M5Stack-style development device**, and a **Hak5-style cybersecurity appliance**.

---

## 4. Design Language

The Hakputer Pro CM5 should look like a fusion of **M5Stack** and **Hak5**, without directly copying either company’s existing products.

### M5Stack-inspired traits

- Modular geometry
- Maker-friendly layout
- Clearly labeled ports
- Visible screws
- Compact blocky shape
- Expansion-first thinking
- Sensor and Grove support
- Friendly but technical UI
- Colored function accents
- Stackable accessory logic

### Hak5-inspired traits

- Dark cyber-tool aesthetic
- Rugged black shell
- Orange/yellow highlights
- Field-ready design
- Security workflow focus
- Payload/device management orientation
- Professional cybersecurity-tool feel
- Cloud C²-style dashboard logic
- Compact tool/appliance identity

### Combined result

The product should feel like:

> A rugged black field terminal with a maker-friendly modular faceplate, clear labeled ports, a physical keyboard, a custom security-focused OS, and a removable primary data SSD.

---

## 5. Core Hardware

The Hakputer Pro CM5 would be based on a **CM5-class Linux computer**, giving it enough power to run a proper operating system, local apps, dashboards, training labs, device managers, and containerized tools.

### Core hardware list

- CM5-class compute module
- Internal eMMC or UFS storage for the OS
- 4 GB, 8 GB, or higher RAM options
- Touchscreen display
- Physical keyboard
- USB-A
- USB-C
- Ethernet
- microSD slot
- Dual-band Wi-Fi: 2.4 GHz and 5 GHz
- Bluetooth / BLE
- NFC / RFID tap zone
- IR transmitter
- IR receiver
- GPIO / pogo-pin connector
- Grove / sensor connector
- Expansion bay
- Internal battery
- Docking contacts
- Cooling system
- Optional second Wi-Fi adapter for authorized lab work
- Optional RF expansion cartridge bay
- Tool-less interchangeable 2.5-inch SSD accessory storage bay

The device should be **semi-modular**. Not everything should require an external module, but the user should still be able to expand the device through ports, cartridges, docks, and sensor modules.

---

## 6. Storage Architecture

Storage is one of the most important parts of the concept.

The Hakputer Pro CM5 has **two separate storage layers**:

1. Internal OS storage
2. Interchangeable accessory SSD storage

### 6.1 Internal OS Storage

The internal storage is reserved for:

- Hakputer OS
- System files
- Critical boot files
- Recovery tools
- Security updates
- Core drivers
- Base applications

This storage should be stable, protected, and not treated as the user’s main working drive.

### 6.2 Interchangeable Accessory SSD

The main working storage would be a **full-size interchangeable SSD**, ideally a **2.5-inch SATA SSD cartridge** or similarly rugged removable drive.

Possible names:

- Accessory SSD
- Primary Data SSD
- Non-OS Storage Cartridge

This drive would be used for:

- Files
- Projects
- Reports
- Logs
- Captured data
- Training labs
- Payload packs
- Modules
- App data
- Documentation
- Offline packages
- Field notes
- Client/lab workspaces
- Backups
- Accessories and downloadable content

The key rule is:

> The OS lives internally. The work lives on the removable SSD.

This lets users swap drives depending on the job, lab, client, school program, or project. One SSD could be for training, one for IoT projects, one for field work, one for a private lab, and one for archived reports.

### 6.3 SSD Bay Requirements

The SSD bay should be:

- Tool-less
- Locking
- Rugged
- Clearly labeled
- Accessible from the front, bottom, side, or rear
- Possibly hot-swappable where safe
- Usable while docked
- Treated as the primary non-OS storage location by the operating system

The UI should clearly state:

```text
Internal Storage: OS and system files
Accessory SSD: primary data storage
```

---

## 7. Hakputer OS

The device would run a custom Linux-based operating system called **Hakputer OS**.

Hakputer OS should not feel like a normal Linux desktop first. It should feel like a purpose-built console interface.

### Home screen modes

- Field Console
- Lab / Education
- IoT Builder
- Blue Team
- Red Team
- Cloud C²
- Devices
- Store

### Top status bar

The top bar should show:

- Battery
- Wi-Fi
- Bluetooth / BLE
- Ethernet
- Cloud status
- Active radios
- Accessory SSD status
- Connected device count

### Side status panel

The side panel could show:

- Connected devices
- Active modules
- Cloud C² status
- Accessory SSD capacity
- Recent downloads
- Module updates
- Warnings or scope status

---

## 8. Operating Modes

### 8.1 Field Console Mode

General-purpose field terminal mode.

Used for:

- Terminal access
- Device setup
- Network notes
- Serial console work
- Quick diagnostics
- Field documentation
- Local dashboards
- Connecting to external equipment

This is the “workbench in your hand” mode.

---

### 8.2 Lab / Education Mode

Controlled learning and training mode.

Could include:

- Cybersecurity lessons
- CTF-style labs
- IoT tutorials
- Wireless safety demos
- USB security awareness labs
- NFC/RFID education
- Linux training
- Networking basics
- Offline documentation

This mode should be beginner-friendly and safe by default.

---

### 8.3 IoT Builder Mode

The M5Stack-inspired maker mode.

Supports:

- Sensor modules
- Grove modules
- Serial devices
- GPIO
- I2C
- SPI
- UART
- Small dashboards
- Data logging
- Prototyping
- Environmental monitoring
- Device automation
- M5Stack-style accessories

This mode makes the device useful beyond cybersecurity. It becomes a field IoT development station.

---

### 8.4 Blue Team Mode

Defensive security mode.

Focuses on:

- Asset inventory
- Local network visibility
- Logs
- Device records
- Incident notes
- Packet review
- USB device history
- Wi-Fi environment awareness
- Report collection
- Evidence organization
- Defensive checklists

This should be the default professional security mode because it frames the device as useful for protection, monitoring, and documentation.

---

### 8.5 Red Team Mode

Red Team Mode exists, but it must be designed around **authorized security work only**.

It should require a project or engagement profile before advanced workflows unlock.

A Red Team project profile could include:

- Project name
- Authorized environment
- Scope
- Dates
- Rules of engagement
- Operator identity
- Logging settings
- Report folder
- Connected tools
- Approved payload packs

This mode should not be a random “attack mode.” It should be a professional mode for legal labs, internal testing, school environments, and approved security engagements.

It would focus on:

- Scope management
- Device coordination
- Notes
- Evidence capture
- Reporting
- Lab payload organization
- Connected Hak5 hardware management
- Cloud C² integration
- Authorized test workflows

The key design principle:

> No scope, no advanced Red Team workflow.

That keeps the device serious, responsible, and professional.

---

### 8.6 Cloud C² Mode

Cloud C² Mode turns the device into a local or remote management console for compatible tools.

It could allow the user to:

- See connected devices
- Register hardware
- Manage field devices
- Sync projects
- Pull down approved packages
- Push configuration profiles
- Review status
- Organize reports
- Manage local and cloud dashboards

The Hakputer could either connect to an existing Cloud C² server or run a local/private lab version for offline use.

---

### 8.7 Devices Mode

Devices Mode is the hardware control center.

It should show everything connected to the Hakputer:

- Built-in Wi-Fi radios
- Bluetooth / BLE
- Ethernet
- NFC/RFID reader
- IR transmitter/receiver
- USB devices
- Hak5-style hardware
- M5Stack-style modules
- Grove sensors
- RF cartridges
- Serial devices
- Cameras
- Storage devices
- Docking station
- Battery modules
- Accessory SSD

The idea is simple:

> Plug something in, and Hakputer OS knows what it is, what driver it needs, what apps work with it, and where to manage it.

---

### 8.8 Store Mode

The device needs a built-in **on-device store** or **package center**.

This is important because the user should not need a laptop to prepare the device.

The Store would allow direct downloads for:

- Apps
- Drivers
- Firmware
- Payload packs
- Training labs
- Offline manuals
- Module support
- Cloud C² connectors
- Report templates
- UI plugins
- Recovery tools
- M5Stack module packages
- Hak5 hardware integrations

Downloads should install directly to the **Accessory SSD** unless they are system-level updates.

The store should clearly separate:

```text
System Updates -> internal OS storage
Apps / Labs / Payload Packs / Projects -> accessory SSD
```

---

## 9. Accessory and Expansion System

The Hakputer Pro CM5 should support both built-in capability and external expansion.

Supported accessories and expansion paths could include:

- M5Stack-style sensor modules
- Grove modules
- USB Hak5-style devices
- Ethernet tools
- RF cartridges
- NFC/RFID accessories
- IR tools
- Docking station
- Battery grip
- Camera module
- GPS/GNSS module
- Environmental sensors
- Serial debugging adapters
- External Wi-Fi adapters for authorized lab use
- Swappable SSD cartridges

The most important accessory is the **SSD cartridge**, because it defines how the device handles project memory and non-OS data.

---

## 10. On-Device Download System

The Hakputer should be self-contained enough that a user can set it up directly from the device.

Hakputer OS should include a built-in download and package center for:

- Device integrations
- Hardware drivers
- Training labs
- Firmware updates
- UI plugins
- Reporting templates
- Defensive tools
- Authorized red-team tool packs
- Cloud C² connectors
- Documentation and offline manuals

The default install location for non-system content should be the **Accessory SSD**.

---

## 11. Security and Responsible-Use Guardrails

Because this device concept includes cybersecurity workflows, wireless interfaces, USB device management, NFC/RFID support, RF expansion, and red-team mode, the design should include strong guardrails.

Recommended guardrails:

- Red Team Mode requires an engagement profile
- Advanced workflows require a selected scope
- Logging is enabled by default for professional modes
- Reports are generated into project folders
- Training labs are separated from real environments
- Radio modules are region-aware and compliance-labeled
- Cloud C² connections require clear authorization
- The OS distinguishes lab, defensive, and professional workspaces

Core rule:

> The Hakputer is for authorized security work, education, diagnostics, and building — not unauthorized access.

---

## 12. Short Product Pitch

**Hakputer Pro CM5 is a CM5-based portable cyberdeck and field operations terminal designed for authorized cybersecurity, IoT building, device management, and field diagnostics. It combines a rugged Hak5-style security-tool body with M5Stack-style modular expansion and maker-friendly hardware. Hakputer OS provides Field Console, Lab/Education, IoT Builder, Blue Team, Red Team, Cloud C², Devices, and Store modes. Internal storage is reserved for the OS, while a tool-less interchangeable full-size SSD cartridge acts as the primary non-OS storage for projects, files, modules, payload packs, labs, captured data, and accessories.**

---

## 13. Product Identity

Possible names:

- Hakputer Pro CM5
- Hakputer Field Console
- Hakputer CM5 Cyberdeck
- Hakputer Pro Field Terminal

Best current name:

> **Hakputer Pro CM5**

Best tagline:

> **Portable Cyberdeck + Field Operations Terminal**
