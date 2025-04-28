# L293D Motor Driver PCB Design (KiCad)

![L293D Motor Driver PCB](./Screenshot%202025-04-28%20130254.png)

## 🛠️ Project Overview

This project features a compact **L293D Motor Driver PCB** designed using **KiCad**.  
The board is ideal for controlling DC motors and small stepper motors in robotics and automation projects.

### ✨ Key Features
- Based on **L293D** dual H-bridge motor driver IC
- Designed for **4 inputs** and **2 motor outputs**
- **Screw terminals** for easy motor and power connections
- **Onboard power LED indicator**
- **Heat sink mounting** for thermal management
- **Compact and clean** layout
- Custom text "**DESIGNED BY AFEEZ**" proudly displayed on the PCB

---

## 📂 Contents

- `L293D_Motor_Driver.kicad_pcb` — KiCad PCB design file
- `L293D_Motor_Driver.sch` — KiCad schematic file
- `project_files/` — Folder containing Gerber files for manufacturing
- `Screenshot 2025-04-28 130254.png` — Rendered 3D view of the PCB

---

## ⚙️ How It Works

The **L293D IC** receives control signals through the **4 input pins** (labeled INT1–INT4) and drives two DC motors or one stepper motor accordingly.  
External motor power is supplied via the terminal block, and a heat sink can be attached to improve high-current operation.

### 🔌 Basic Connections
- `J1` — Inputs (control signals from microcontroller)
- `J2`, `J4` — Motor outputs
- `Top Terminal Block` — Motor voltage supply (Vcc2) and ground

---

## 🧰 Requirements

- **KiCad 6.0+** for opening and editing the design files
- Basic understanding of **motor driver circuits** and **PCB design**

---

## 🚀 Getting Started

1. Clone or download this repository.
2. Open the `.kicad_pro` project file using KiCad.
3. Customize or modify the design according to your project needs.
4. Export Gerber files to manufacture your PCB.

---

## 📄 License

This project is licensed under the **MIT License**.  
Feel free to use, modify, and share it with proper attribution!

---

## 🙏 Acknowledgments

Designed and developed with love for learning and sharing.  
**– Afeez**
