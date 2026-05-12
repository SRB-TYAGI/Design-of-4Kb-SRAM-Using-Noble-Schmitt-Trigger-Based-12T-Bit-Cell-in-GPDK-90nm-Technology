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
  <img src="Images/SRAM Architecture.png" alt="12T SRAM Architecture" width="700"/>
</p>

<p align="center">
  <b>Fig:-1. Proposed 12T SRAM Cell Architecture</b>
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
  <b>Fig:-2. Schematic Representation of Proposed 12T SRAM Cell in Cadence Virtuoso</b>
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
  <b>Fig:-3. Symbolic Representation of Proposed 12T SRAM Cell</b>
</p>


# 🔷 Pre-Layout Simulation of Proposed 12T SRAM Cell

The pre-layout simulation of the proposed **12T SRAM Cell** was performed in **Cadence Virtuoso** using **GPDK 90nm Technology** to verify the functional correctness of the SRAM architecture before physical layout implementation.

The simulation setup includes:
- **Power Supply Connections (VDD/GND)**
- **Control Signal Inputs**
- **Differential Write Bitlines (BL / BLB)**
- **Read Word Line (RWL)**
- **Read Bitline (RBL)**
- **Storage Node Outputs (Q / QB)**

### 📌 Objectives of Pre-Layout Simulation
- Verify SRAM functional operation
- Analyze Read, Write, and Hold operations
- Validate switching behavior of Q and QB
- Evaluate SRAM stability before layout generation
- Ensure proper operation of control and read/write paths

### 📌 Features Verified
- Correct Read Operation
- Successful Write Operation
- Stable Hold Condition
- Differential Bitline Functionality
- Proper Read Bitline Response

<p align="center">
  <img src="Images/Pre-Layout Simulation of Proposed 12T SRAM Cell.png" alt="Pre-Layout Simulation of Proposed 12T SRAM Cell" width="900"/>
</p>

<p align="center">
  <b>Fig:-4. Pre-Layout Simulation Setup of Proposed 12T SRAM Cell</b>
</p>

# 🔷 Transient Analysis

Transient analysis of the proposed **12T SRAM Cell** was performed in **Cadence Virtuoso** to verify the dynamic behavior of the SRAM during **Read**, **Write**, and **Hold** operations.

The simulation demonstrates the switching characteristics of:
- **Word Line (WL)**
- **Bitlines (BL / BLB)**
- **Read Bitline (RBL)**
- **Storage Nodes (Q / QB)**

### 📌 Objectives of Transient Analysis
- Verify read operation
- Verify write operation
- Analyze hold stability
- Observe switching behavior of storage nodes
- Evaluate dynamic SRAM performance

### 📌 Observations
- Successful data writing and retention
- Proper complementary switching of Q and QB
- Stable read operation through RBL
- Reliable transient response

<p align="center">
  <img src="Images/Transient Analysis.png" alt="Transient Analysis of Proposed 12T SRAM Cell" width="950"/>
</p>

<p align="center">
  <b>Fig. Transient Analysis of Proposed 12T SRAM Cell</b>
</p>


# 🔷 DC Simulation for Butterfly Curve and SNM Evaluation

DC simulation was performed in **Cadence Virtuoso** using **GPDK 90nm Technology** to evaluate the stability of the proposed **12T SRAM Cell** through butterfly curve analysis.

The butterfly curve was obtained by plotting the voltage transfer characteristics (VTC) of two cross-coupled inverters. The maximum square that can fit inside the butterfly curve represents the **Static Noise Margin (SNM)** of the SRAM cell.

### 📌 Objectives of DC Simulation
- Evaluate SRAM stability
- Measure Static Noise Margin (SNM)
- Analyze read and hold stability
- Verify noise immunity of the SRAM cell

### 📌 Parameters Evaluated
- **Read Static Noise Margin (RSNM)**
- **Hold Static Noise Margin (HSNM)**
- **Write Static Noise Margin (WSNM)**

### 📌 Features Observed
- Improved SRAM stability
- Better noise tolerance
- Enhanced reliability under process variations

<p align="center">
  <img src="Images/DC Simulation.png" alt="DC Simulation Butterfly Curve" width="850"/>
</p>

<p align="center">
  <b>Fig. DC Simulation for Butterfly Curve and SNM Evaluation of Proposed 12T SRAM Cell</b>
</p>

# 🔷 Monte Carlo Analysis of Proposed 12T SRAM Cell

Monte Carlo analysis was performed in **Cadence Virtuoso** using **GPDK 90nm Technology** to evaluate the impact of process variations on the stability and reliability of the proposed **12T SRAM Cell**.

The analysis helps in verifying the robustness of the SRAM cell under random variations in transistor parameters such as:
- Threshold Voltage Variations
- Channel Length Variations
- Oxide Thickness Variations
- Process Corners

Monte Carlo simulations were carried out for:
- **Write Static Noise Margin (WSNM)**
- **Hold Static Noise Margin (HSNM)**
- **Read Static Noise Margin (RSNM)**

The obtained results demonstrate improved SRAM stability and tolerance against manufacturing variations.

---

# 🔷 WSNM Monte Carlo Curve of 12T SRAM Cell

The Monte Carlo analysis for **Write Static Noise Margin (WSNM)** was performed to evaluate the write capability and reliability of the SRAM cell under process variations.

### 📌 Observations
- Stable write operation
- Improved write reliability
- Better tolerance against variations

<p align="center">
  <img src="Images/WSNM Monte Carlo Curve of 12-T SRAM Cell.png" alt="WSNM Monte Carlo Curve" width="850"/>
</p>

<p align="center">
  <b>Fig. WSNM Monte Carlo Curve of Proposed 12T SRAM Cell</b>
</p>

---

# 🔷 HSNM Monte Carlo Curve of 12T SRAM Cell

The Monte Carlo analysis for **Hold Static Noise Margin (HSNM)** was performed to verify the data retention capability of the SRAM cell during hold condition.

### 📌 Observations
- Stable data retention
- Improved hold stability
- Enhanced noise immunity

<p align="center">
  <img src="Images/HSNM Monte Carlo Curve of 12-T SRAM Cell.png" alt="HSNM Monte Carlo Curve" width="850"/>
</p>

<p align="center">
  <b>Fig. HSNM Monte Carlo Curve of Proposed 12T SRAM Cell</b>
</p>

---

# 🔷 RSNM Monte Carlo Curve of 12T SRAM Cell

The Monte Carlo analysis for **Read Static Noise Margin (RSNM)** was performed to evaluate the read stability of the SRAM cell under process variations.

### 📌 Observations
- Reliable read operation
- Reduced read disturb issues
- Improved read stability

<p align="center">
  <img src="Images/RSNM Monte Carlo Curve of 12-T SRAM Cell.png" alt="RSNM Monte Carlo Curve" width="850"/>
</p>

<p align="center">
  <b>Fig. RSNM Monte Carlo Curve of Proposed 12T SRAM Cell</b>
</p>

# 🔷 Dynamic Power Analysis of Proposed 12T SRAM Cell

Dynamic power analysis was performed in **Cadence Virtuoso** using **GPDK 90nm Technology** to evaluate the switching power consumption of the proposed **12T SRAM Cell** during SRAM operations.

The dynamic power consumption is mainly caused by:
- Charging and discharging of bitlines
- Wordline switching activity
- Internal node transitions

### 📌 Monte Carlo Analysis Results
- **Number of Samples** : 1000
- **Mean Dynamic Power** : 660.859 nW
- **Standard Deviation** : 14.4676 nW

### 📌 Observations
- Stable dynamic power distribution
- Reduced switching power consumption
- Improved power efficiency during SRAM operation

<p align="center">
  <img src="Images/Monte Carlo curve of Dynamic Power of 12T SRAM Cell.jpg" alt="Monte Carlo Curve of Dynamic Power of 12T SRAM Cell" width="850"/>
</p>

<p align="center">
  <b>Fig. Monte Carlo Curve of Dynamic Power of Proposed 12T SRAM Cell</b>
</p>

---

# 🔷 Leakage Power Analysis of Proposed 12T SRAM Cell

Leakage power analysis was performed to evaluate the standby power consumption of the proposed **12T SRAM Cell** under idle conditions.

Leakage power mainly occurs due to:
- Subthreshold Leakage Current
- Gate Oxide Leakage
- Junction Leakage Current

### 📌 Monte Carlo Analysis Results
- **Number of Samples** : 1000
- **Mean Leakage Power** : 156.807 µW
- **Standard Deviation** : 5.13059 µW

### 📌 Observations
- Stable leakage power distribution
- Improved standby power efficiency
- Better low-power SRAM performance

<p align="center">
  <img src="Images/Monte Carlo curve of Leakage Power of 12T SRAM Cell.jpg" alt="Monte Carlo Curve of Leakage Power of 12T SRAM Cell" width="850"/>
</p>

<p align="center">
  <b>Fig. Monte Carlo Curve of Leakage Power of Proposed 12T SRAM Cell</b>
</p>






# 📊 Simulations Performed

## ✅ Write Operation
- Verified successful data overwrite
- Evaluated **Write Static Noise Margin (WSNM)**

- 
## ✅ Hold Operation
- Verified stable data retention
- Evaluated **Hold Static Noise Margin (HSNM)**



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
