# NanoStat Firmware – ESP32 DevKit V1
## Background
This project is based on the open-source NanoStat project:

Shawn Chia-Hung Lee, Peter J. Burke  
“NanoStat: An open source, fully wireless potentiostat”  
Electrochimica Acta, 2022  
DOI: https://doi.org/10.1016/j.electacta.2022.140481

Original repository:
https://github.com/PeterJBurke/Nanostat

The original NanoStat implementation uses ESP32-PICO hardware and provides a fully wireless potentiostat system with a web-based user interface.  
In this work, the firmware and hardware were modified to operate on ESP32 DevKit V1.


## Purpose of This Repository
This repository was created for academic purposes (Kerja Praktik).

Main objectives:
- Study NanoStat firmware architecture
- Modify firmware to support a different ESP32 module and hardware design
- Port firmware from ESP32-PICO to ESP32 DevKit V1
- Design compatible hardware
- Verify firmware compatibility
- Test the system on real hardware


## Modification
Original board:
ESP32-PICO

Modified board:
ESP32 DevKit V1

Changes include:
- Board configuration update in `platformio.ini`
- Pin remapping in firmware
- Minor compatibility fixes
- Custom PCB design
- Hardware assembly and testing

The modified firmware and hardware has been successfully built and tested.


## Current Status
- Firmware builds successfully  
- Runs on ESP32 DevKit V1  
- Web interface works  
- Hardware assembled  
- System tested successfully  


## Build Environment
- PlatformIO
- Visual Studio Code
- ESP32 DevKit V1
- Arduino framework


## Web Interface
The web-based UI files are located in the `data/` directory
and are uploaded to the ESP32 filesystem (SPIFFS/LittleFS).


## License
This project follows the original NanoStat license (MIT License).

All credit for the original design belongs to:
Peter J. Burke et al.

This repository contains firmware and hardware modifications
for academic and research purposes.
