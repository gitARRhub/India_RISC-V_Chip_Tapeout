# 📘 Week 0: Tool Installation Log

Welcome to my RISC-V tapeout journey! This Week 0 log captures the setup of three essential tools for digital design and simulation.

---
# 🧰 System Requirements
# Make sure your system has:
 • 6 GB RAM
 
 • 50 GB HDD
 
 • Ubuntu 20.04 or higher
 
 • 4 vCPU
 

## 🧰 Tools Installed

                                          | Tool             | Purpose                    | Status        |
                                          |------------------|-----------------------------|----------------|
                                          | **Yosys**         | RTL synthesis               | ✅ Installed    |
                                          | **Icarus Verilog**| Verilog simulation          | ✅ Installed    |
                                          | **GTKWave**       | Waveform visualization      | ✅ Installed    |

---

## 🛠️ Installation Steps

### 🔹 Yosys – Synthesis Tool
```bash
sudo apt update
sudo apt install yosys
```
**Check version:**
```bash
yosys -V
```
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

---

### 🔹 GTKWave – Waveform Viewer
```bash
sudo apt install gtkwave
```
**Launch GUI:**
```bash
gtkwave
```
> Visualizes simulation outputs from Icarus Verilog.

---
