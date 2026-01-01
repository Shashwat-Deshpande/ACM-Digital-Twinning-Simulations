### ACM India Winter School 2025

**Authors:** Shashwat Atul Deshpande  
**Institution:** Shri Ramdeobaba College of Engineering and Management, Nagpur

---

## 📖 Overview

This repository documents the simulation modeling projects developed during the **ACM India Winter School 2025**. The work explores two distinct simulation paradigms:
1.  **System Dynamics (SD):** For analyzing high-level policy feedback loops and non-linear behavior.
2.  **Discrete Event Simulation (DES):** For analyzing operational efficiency, queuing systems, and resource allocation.

---

## 🚀 Project 1: NextGen Crypto Digital Twin (System Dynamics)
**Focus:** Strategic Policy Analysis & Feedback Loops  
**Tool:** Vensim

### Description
A System Dynamics Digital Twin simulating the feedback loops between cryptocurrency adoption and financial crime. Features a **'Parallel Stock' architecture** to monitor the **shadow economy** and evaluate the long-term impact of regulatory policies.

Unlike linear models, this simulation captures the dynamic "cat-and-mouse" game between regulators and illicit actors, revealing how system delays can cause well-intentioned policies to fail.

### Key Features
* **Multi-Sector Integration:** Connects **Social** (Trust/Adoption), **Legal** (Government Control), and **Criminal** (Illicit Activity) sectors.
* **Shadow Economy Tracking:** Utilizes a "Parallel Stock" structure to simulate hidden funds that exist outside the visible, regulated system.
* **Policy Resistance:** Demonstrates how sudden, reactionary bans can paradoxically increase the "detection delay," driving crime deeper underground rather than eliminating it.

---

## 🛠️ Project 2: ATM Queue Optimization (Discrete Event Simulation)
**Focus:** Operational Efficiency & Bottleneck Analysis  
**Tool:** AnyLogic

### Description
A foundational Discrete Event Simulation (DES) developed to explore the core mechanics of the AnyLogic Process Modeling Library. This project serves as a **technical study** on queuing theory (M/M/1 systems), agent generation, and resource seizing.

The model simulates a single-server banking environment to determine the tipping point where arrival rates overwhelm service capacity, leading to exponential wait times.

### Technical Highlights
* **Process Modeling:** Implementation of `Source` → `Queue` → `Seize` → `Delay` → `Sink` logic.
* **Resource Management:** Dynamic allocation of server units (ATM) to incoming agents.
* **Data Visualization:** Real-time statistical collection of `TimeInSystem` and `QueueLength` to identify operational bottlenecks.
