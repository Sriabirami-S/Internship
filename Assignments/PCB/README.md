# Motion Detection PCB Design

## Introduction
This project involves designing a basic motion detection circuit using a PIR (Passive Infrared) sensor. The goal was to create a compact and reliable PCB layout that interfaces a PIR sensor with an ESP8266 and other passive components. The entire board was designed in KiCad 7, from schematic to 3D view.

## Design Overview
- **Sensor Module:** HC-SR501 PIR sensor  
- **Microcontroller:** ESP8266MOD (NodeMCU)  
- **Voltage Regulator:** AMS1117 (3.3V LDO)  
- **Output:** LED indicator  
- **Software Used:** KiCad 7  

## Circuit Description
The PIR sensor detects motion and sends a HIGH signal to the ESP8266. The ESP8266 can then be programmed to trigger actions like lighting an LED or uploading data to a cloud service such as Google Sheets. The AMS1117 regulator is used to step down 5V input to 3.3V for the ESP8266.

## PCB Design Steps
1. **Schematic Creation:** Designed using KiCad with accurate pin mappings  
2. **Footprint Assignment:** Custom footprints for the ESP8266 and PIR sensor were added  
3. **Routing:** 2-layer PCB with clean and short signal paths  
4. **3D Visualization:** Verified in KiCad’s 3D Viewer  

## Design Files Provided
- `pcb schematic.pdf` – Complete circuit schematic  
- `pcb F_Cu.pdf` – Front copper layer  
- `pcb edge cuts.pdf` – PCB boundary outline  
- `README.md` – Documentation  

## Conclusion
This project provided hands-on experience in converting a simple motion-sensing circuit into a professional-quality PCB. It helped strengthen skills in schematic design, component layout, PCB routing, and preparation of Gerber files for manufacturing.

## View Work
All design files are included in this folder for review and fabrication.

