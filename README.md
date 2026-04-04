# 🔌 Relay Module PCB

A compact **5V Relay Module PCB** designed using Proteus 8 Professional for controlling high-power loads using low-power digital signals.

---

## 📌 Overview
This project implements a transistor-driven relay circuit and converts it into a PCB layout.  
It allows microcontrollers like Arduino to safely and efficiently switch electrical appliances.

📏 **PCB Dimensions:** 34mm × 53mm

---

## ⚙️ Features
- 5V relay switching  
- Transistor-based driver circuit  
- Flyback diode protection  
- LED indicates relay activation (ON state)  
- Compact PCB design  

---

## 🛠️ Components
- 5V Relay  
- NPN Transistor (BC547 / 2N2222)  
- Diode (Flyback Protection)  
- Resistors (including base resistor for transistor biasing)  
- LED  

---

## 🔄 Working
A 5V digital input signal is applied to the transistor base through a resistor.  
This turns the transistor ON, allowing current to flow through the relay coil.  
The relay gets energized and switches the connected load.  

A flyback diode protects the circuit from voltage spikes, and the LED indicates when the relay is active.

---

## 🖼️ Preview

### 🔹 Schematic
![Schematic](https://github.com/user-attachments/assets/5564f5d2-f3a4-448e-86e8-1b18e589438c)

### 🔹 PCB Layout
![PCB](https://github.com/user-attachments/assets/9236ef49-e22f-4971-87b6-ba0f07f093b5)

---

## 🔌 Applications
- Home automation  
- Arduino / IoT projects  
- Appliance control  

---

## ⭐ Support
If you like this project, consider giving it a ⭐ on GitHub!
