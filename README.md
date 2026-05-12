# Design of 4Kb SRAM Using Noble Schmitt Trigger-Based 12T Bit Cell in GPDK 90nm Technology

This repository contains the complete **Senior Design Project (Final Year Project)** on the design and analysis of a **4Kb SRAM** using a **Noble Schmitt Trigger-Based 12T SRAM Bit Cell** in **GPDK 90nm Technology** using **Cadence Virtuoso**.

The project focuses on improving **SRAM Stability**, **Read/Write Reliability**, and **Noise Immunity** using a **Schmitt Trigger-Based 12T Architecture** with **Separate Read and Write Paths**.

---

# 📌 Introduction

Static Random Access Memory (**SRAM**) is widely used in high-speed memory applications due to its fast access time and low latency. However, conventional SRAM cells suffer from challenges such as reduced stability, read disturb issues, and poor noise immunity at scaled technologies.

This project proposes a **Schmitt Trigger-Based 12T SRAM Cell** to enhance:
- **Read Stability**
- **Write Reliability**
- **Noise Immunity**
- **Process Variation Tolerance**

The complete design was implemented and verified using **Cadence Virtuoso** in **GPDK 90nm CMOS Technology**.

---

# 🎯 Project Objectives

- Design a robust **12T SRAM Bit Cell**
- Improve **SRAM Stability**
- Reduce **Read Disturb Issues**
- Analyze **Read, Write, and Hold Operations**
- Evaluate **RSNM, HSNM, and WSNM**
- Perform **Monte Carlo Analysis**
- Implement **Custom Layout Design**
- Perform **DRC/LVS Verification**
- Perform **RC Extraction & Post-Layout Validation**

---

# 🛠️ Tools & Technologies Used

- **Cadence Virtuoso**
- **GPDK 90nm Technology**
- **CMOS VLSI Design**
- **Analog & Mixed Signal Simulation**
- **Custom Layout Design**
- **DRC / LVS Verification**
- **RC Extraction**

---

# 🧠 SRAM Architecture

<p align="center">
  <img src="Images/SRAM Architecture.png" width="600"/>
</p>

The proposed **12T SRAM Architecture** consists of:

The proposed **12T SRAM Architecture** consists of:
- Cross-Coupled Inverters
- Schmitt Trigger-Based Feedback
- Separate Read/Write Paths
- Differential Bitlines
- Enhanced Stability Structure

The architecture improves:
- **Read Stability**
- **Write Reliability**
- **Noise Immunity**
- **Process Variation Tolerance**

The architecture improves SRAM performance by increasing stability and reducing noise sensitivity during read and write operations.

---
# 🔷 Schematic Representation of Proposed 12T SRAM Cell

The schematic of the proposed **12T SRAM Cell** was designed and simulated using **Cadence Virtuoso** in **GPDK 90nm Technology**. The design incorporates a **Schmitt Trigger-Based Feedback Structure** with **separate read and write paths** to improve SRAM stability and reliability.



<p align="center">
  <img src="Images/Schematic representatio of  Proposed 12T SRAM cell..png" alt="12T SRAM Schematic in Cadence Virtuoso" width="850"/>
</p>

<p align="center">
  <b>Fig. Schematic Representation of Proposed 12T SRAM Cell in Cadence Virtuoso</b>
</p>
# 🔷 Symbolic Representation of Proposed 12T SRAM Cell

The symbolic representation of the proposed **12T SRAM Cell** was created in **Cadence Virtuoso** to simplify hierarchical design integration and simulation. The symbol includes all essential input, output, control, and power pins required for SRAM operations.

### 📌 Features of the Symbol
- **Compact and Modular Design**
- **Easy Hierarchical Integration**
- **Separate Read and Write Control Signals**
- **Differential Write Bitlines (BL / BLB)**
- **Dedicated Read Bitline (RBL)**
- **Power Supply Pins (VDD / GND)**
- **Storage Node Outputs (Q / QB)**

### 📌 Pins Description
- **WL** → Write Word Line
- **RWL** → Read Word Line
- **BL / BLB** → Differential Write Bitlines
- **RBL** → Read Bitline
- **Q / QB** → Stored Data Outputs
- **CONTROL** → Control Signal for SRAM Operation
- **VDD / GND** → Power Supply Connections

<p align="center">
  <img src="Images/Symbolic Representation of Proposed 12T SRAM Cell.png" alt="Symbolic Representation of Proposed 12T SRAM Cell" width="500"/>
</p>

<p align="center">
  <b>Fig. Symbolic Representation of Proposed 12T SRAM Cell</b>
</p>


# 📊 Simulations Performed

## ✅ Hold Operation
- Verified stable data retention
- Evaluated **Hold Static Noise Margin (HSNM)**

## ✅ Write Operation
- Verified successful data overwrite
- Evaluated **Write Static Noise Margin (WSNM)**

## ✅ Read Operation
- Verified stable read functionality
- Evaluated **Read Static Noise Margin (RSNM)**

## ✅ Monte Carlo Analysis
- Process variation analysis
- Statistical reliability evaluation
- Dynamic and leakage power analysis

---

# 📈 Results

| Parameter | Value |
|------------|------------|
| **WSNM** | **664.59 mV** |
| **HSNM** | **430.80 mV** |
| **RSNM** | **309.07 mV** |

The proposed SRAM cell demonstrated:
- Improved Stability
- Better Noise Immunity
- Reliable Read/Write Operations
- Robust Performance under Process Variations

---

# 🧩 Physical Verification

## ✅ DRC (Design Rule Check)
No DRC violations were found in the layout.

## ✅ LVS (Layout Versus Schematic)
The layout successfully matched the schematic.

## ✅ RC Extraction
Parasitic resistance and capacitance were successfully extracted for post-layout analysis.

---

# 📂 Repository Structure

```text
├── Schematic/
├── Layout/
├── Simulations/
├── Monte_Carlo_Analysis/
├── DRC_LVS_Reports/
├── RC_Extraction/
├── Waveforms/
├── Final_Report/
└── Images/
```

---

# 📷 Project Includes

- 12T SRAM Schematic
- SRAM Symbol Design
- Layout Design
- Read/Write/Hold Waveforms
- Monte Carlo Simulation Results
- DRC/LVS Reports
- RC Extraction Results

---

# 🎯 Applications

- Cache Memory
- Embedded Systems
- Low-Power VLSI Systems
- High-Speed SRAM Arrays
- Radiation-Hardened Electronics
- Space Applications

---

# 👨‍💻 Team Members

- **Sourabh Tyagi**
- **Garv Kumar Sharma**
- **Aditya Thakur**

---

# 🙏 Acknowledgement

Special thanks to **Dr. Praveen Maurya** and the **School of Electronics Engineering, VIT-AP University** for continuous guidance and support throughout this project.

---

# ⭐ Conclusion

The proposed **Schmitt Trigger-Based 12T SRAM Architecture** successfully improved:
- SRAM Stability
- Noise Immunity
- Read/Write Reliability

The project demonstrated robust performance through **pre-layout and post-layout simulations**, making it suitable for **low-power and high-reliability SRAM applications**.

---

# 🔗 Keywords

`SRAM` `12T SRAM` `Cadence Virtuoso` `GPDK90nm` `CMOS` `VLSI` `Schmitt Trigger` `Memory Design` `Layout Design` `DRC` `LVS` `RC Extraction` `Monte Carlo Analysis` `Low Power VLSI`
