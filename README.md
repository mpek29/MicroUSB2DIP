# MicroUSB2DIP

## 🚀 Overview
![Main Preview](assets/img/main.png)

This is an open-source reverse-engineered version of a Micro USB to DIP adapter, based on the original component available [here](https://fr.aliexpress.com/item/32947889760.html). The goal of this project was to practice reverse engineering as a learning exercise and to prepare for a future adaptation in a larger project.

## 🎯 Purpose
- 🔍 **Reverse engineering**: Understanding the design and functionality of this micro USB  to DIP connector.
- 🛠️ **Skill development**: Enhancing expertise in PCB design and hardware analysis skills.
- 🔄 **Future adaptation**: Leveraging this knowledge for embedded applications.

## 📝 Features Comparison: Original vs. Reverse-Engineered

| Feature            | Original Module | Reverse-Engineered Version |
|--------------------|----------------|---------------------------|
| 🖥️ PCB Design        | Proprietary     | Open-source & customizable |
| 🔌 Connector Type    | Micro USB       | Micro USB |
| 📌 Pin Mapping      | Standard DIP    | Standard DIP |
| 👐 Mechanical Drawing  | <img src="assets/img/original_pcb.png"> | <img src="assets/img/reversed_pcb.png"> |
| 📝 Reverse-Engineered Schematic | N/A | <img src="assets/img/reversed_sch.png" > |
| 📷 Photo             | <img src="assets/img/original_3d.png"> | <img src="assets/img/reversed_3d.png"> |

## 🛠️ How to Use
### 📌 Wiring Guide
| Pin  | Function |  
|------|----------|  
| VBUS | +5V |  
| D-   | Data - |  
| D+   | Data + |  
| ID   | Mode detect (A: GND, B: Open) |  
| GND  | Ground |  

## 🌟 License
This project is open-source. Feel free to use, modify, and contribute! 🚀
