# 📘 Week 0: Tool Installation

Welcome to my RISC-V tapeout journey! This Week 0 log captures the setup of three essential tools for digital design and simulation.
## 💻 Week 0 Highlights

- ✅ Created this GitHub repository to document my tapeout journey  
- ✅ Summarized the kickoff video and program goals  
- ✅ Installed essential tools for RTL simulation and synthesis  
- ✅ Verified system configuration and tool versions  
- ✅ Captured snapshots  for reproducibility

All setup steps and screenshots are organized in this repository to help others follow along.

---
---
# 🧰 System Requirements

Make sure your system has:

 • 6 GB RAM
 
 • 50 GB HDD
 
 • Ubuntu 20.04 or higher
 
 • 4 vCPU
 

# 🧰 Tools Installed
   | Tool             | Purpose                    | Status        |
   |------------------|-----------------------------|----------------|
   | **Yosys**         | RTL synthesis               | ✅ Installed    |
   | **Icarus Verilog**| Verilog simulation          | ✅ Installed    |
   | **GTKWave**       | Waveform visualization      | ✅ Installed    |

---

# 🛠️ Installation Steps

### 🔹 Yosys – Synthesis Tool
```bash
sudo apt update
sudo apt install yosys
```
**Check version:**
```bash
yosys -V
```
 ![Image Alt](image_url)
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

 ![Image Alt](image_url)
---

### 🔹 GTKWave – Waveform Viewer
```bash
sudo apt install gtkwave
```
**Launch GUI:**
```bash
gtkwave
```

 ![Image Alt](image_url)
> Visualizes simulation outputs from Icarus Verilog.

---
