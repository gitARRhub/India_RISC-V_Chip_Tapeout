# 🚀 Week 0: Tool Installation & Setup

Welcome aboard my RISC-V tapeout journey!  
This Week 0 marks the foundation of my digital design environment—where simulation meets synthesis.  
Whether you're a fellow explorer or just curious, this guide walks you through the essential tools I installed to kickstart RTL development.

---

## 🌟 Week 0 Milestones

- 📁 Created this GitHub repository to document my tapeout progress  
- 🎥 Summarized the kickoff video and outlined program goals  
- 🧰 Installed core tools for RTL simulation, synthesis, and waveform analysis  
- 🧪 Verified system configuration and tool versions  
- 📸 Captured screenshots for reproducibility and clarity  

All steps are documented with visuals to help others replicate the setup with confidence.

---

## 🖥️ System Requirements

| Component     | Minimum Requirement         |
|---------------|-----------------------------|
| 💾 RAM         | 6 GB                        |
| 🗄️ Storage     | 50 GB HDD                   |
| 🧠 CPU         | 4 vCPU                      |
| 🐧 OS          | Ubuntu 20.04 or higher      |

---

## 🔧 Tools Installed

| 🛠️ Tool            | 🔍 Purpose                  | ✅ Status       |
|--------------------|-----------------------------|----------------|
| **Yosys**           | RTL synthesis               | ✅ Installed    |
| **Icarus Verilog**  | Verilog simulation          | ✅ Installed    |
| **GTKWave**         | Waveform visualization      | ✅ Installed    |

---

## 📦 Installation Guide

### 🔹 Yosys – Synthesis Tool
```bash
sudo apt update
sudo apt install yosys
```
**Check version:**
```bash
yosys -version
```
![Image Alt](https://github.com/gitARRhub/India_RISC-V_Chip_Tapeout/blob/main/Week-0/Images/yosys%20installed.png?raw=true)
 
> Used for converting Verilog RTL to gate-level netlists.

---

### 🔹 Icarus Verilog – Simulation Engine
```bash
sudo apt install iverilog
```
**Check version:**
```bash
iverilog -v
```
> Helps simulate Verilog modules and generate `.vcd` files for waveform analysis.

 ![Image Alt](https://github.com/gitARRhub/India_RISC-V_Chip_Tapeout/blob/main/Week-0/Images/iverilog%20installed.png?raw=true)
---

### 🔹 GTKWave – Waveform Viewer
```bash
sudo apt install gtkwave
```
**Check version:**
```bash
gtkwave -version
```
**Launch GUI:**
```bash
gtkwave
```

 ![Image Alt](https://github.com/gitARRhub/India_RISC-V_Chip_Tapeout/blob/main/Week-0/Images/gtk%20installed.png?raw=true)
> Visualizes simulation outputs from Icarus Verilog.

---
