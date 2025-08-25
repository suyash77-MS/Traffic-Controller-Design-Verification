<h1 align="center">🚦 Traffic Light Controller FSM using Verilog & FPGA 🖥️</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Language-Verilog-blue?style=for-the-badge&logo=verilog" />
  <img src="https://img.shields.io/badge/Platform-Basys%203%20(Artix--7)-orange?style=for-the-badge&logo=xilinx" />
  <img src="https://img.shields.io/badge/Tools-Vivado%20%7C%20ModelSim%20%7C%20EDA%20Playground-green?style=for-the-badge&logo=tools" />
  <img src="https://img.shields.io/badge/Domain-Digital%20Design-red?style=for-the-badge&logo=logic" />
</p>

---

## 📖 Project Overview
This project implements a **Finite State Machine (FSM)-based Traffic Light Controller** using **Verilog HDL**, designed and deployed on the **Basys 3 (Artix-7) FPGA board**.  
The controller manages traffic flow at a two-road intersection (**Main Street and Side Street**) with proper **Green → Yellow → Red** light sequencing and state durations.

---

## 📝 Problem Statement
Design a **Traffic Light Controller** that:
- Controls signals for **two intersecting roads** (Main Street & Side Street).  
- Ensures proper **state transitions (Green → Yellow → Red)** for both roads.  
- Resets safely to the initial state on reset signal.  
- Verifies correctness through **simulation and hardware testing**.

---

## 🛠️ Tools Used
- **Xilinx Vivado** → RTL coding, synthesis, FPGA implementation, and waveform simulation  
- **ModelSim** → Functional verification of Verilog design  
- **EDA Playground** → Quick simulation and debugging in a browser environment  
- **Basys 3 (Artix-7)** → Hardware deployment and validation  

---

## ⚙️ Design Methodology
1. **K-map simplification** – Derived Boolean expressions for next-state logic.  
2. **FSM Design** – Modeled traffic lights using a **Moore FSM**.  
3. **RTL Coding** – Implemented FSM with case-statements and parameterized state durations.  
4. **Testbench** – Verified correct light sequences, reset condition, and edge cases.  
5. **Simulation & Verification** – Checked timing diagrams in Vivado/ModelSim.  
6. **FPGA Deployment** – Synthesized and programmed Basys 3 board to observe real-time functionality.  

---

## ✅ Achievements
- Successfully designed and verified a **traffic controller FSM**.  
- Implemented **parameterized durations** for flexibility.  
- Verified **reset functionality and edge cases**.  
- Achieved **hardware validation on Basys 3 FPGA**.  
- Built strong fundamentals in **FSM design, HDL coding, and FPGA tools**.  

---
