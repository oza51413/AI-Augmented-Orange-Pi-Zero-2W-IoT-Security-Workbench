# AI-Augmented Orange Pi Zero 2W IoT Security Workbench

An AI-assisted IoT security workbench built around an **Orange Pi Zero 2W**. The AI connects to the Pi through **SSH** and accesses a dedicated project workspace for security research.

## Recon

Hardware reconnaissance and device documentation, including images and identification of interfaces and components.

## Foothold

Hardware and signal analysis, including:

- Signal analysis and interposition
- UART
- I2C
- JTAG
- Logic analyzer
- Flash memory analysis

## RevEng

Reverse engineering and analysis tools, including:

- Claude
- Wairz
- Ghidra
- GDB

## Parts List

- **Orange Pi Zero 2W** — Main workbench platform
- **UART** — Serial access through the Pi's GPIO pins
- **USB Hat** — Connects external USB tools
- **Logic Analyzer** — Signal capture and analysis
- **Flash Programmer** — Flash memory read/write
- **Alfa Wi-Fi Adapter** — Wireless testing and packet injection
- **Nordic nRF BLE Sniffer** — BLE traffic capture
- **5V Relay** — Controlled switching through GPIO
- **Mini Breadboard** — Mounting and connecting components

>  **Safety:** Voltage levels and pinouts are verified before connecting hardware to avoid damaging the Orange Pi or target devices.

**Status:**  Active Development
