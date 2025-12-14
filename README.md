# Automatic Washing Machine Controller (Verilog FSM)
# Automatic Washing Machine Controller (Verilog FSM)

## 📌 Project Overview
This project implements an FSM-based automatic washing machine controller using Verilog HDL. 
The design supports multiple wash modes, lid safety pause, cancel handling, and sequential 
state transitions from Idle to Spin.

## 🧠 FSM States
- IDLE
- READY
- SOAK
- WASH
- RINSE
- SPIN

## ⚙️ Features
- Mode-based timing control
- Lid safety pause mechanism
- Coin validation and return
- Sequential stage execution
- Fully verified using testbench and waveform analysis

## 🧩 RTL Schematic
![RTL Schematic](schematic/rtl_schematic.png)

## 📊 Simulation Waveform
![Simulation Waveform](simulation/waveform.png)

## 🧪 Verification
- Self-written testbench
- Simulated in Vivado / ModelSim
- Verified all state transitions and safety conditions

## 🛠 Tools Used
- Verilog HDL
- Vivado / ModelSim
- GTKWave (optional)

## 👨‍💻 Author
**Gopal Mandal**  
B.Tech ECE, NIT Silchar
