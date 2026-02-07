# iPWR Startup Transient Analysis (0% to 100% Power)

## 📌 Project Overview
This project simulates and analyzes the behavior of an **Integral Pressurized Water Reactor (iPWR)** during a controlled power ascension from a subcritical state (0%) to full power (100%). The study was conducted using the **IAEA iPWR Simulator** as part of the NEM 217 course.

The primary objective was to observe critical physical phenomena such as reactivity feedback, pressurizer dynamics, and thermal-hydraulic coupling during a transient event.

## 👨‍💻 My Contribution & Focus Area
While contributing to the simulation and general analysis of the entire project, **I specifically focused on the Start-Up Rate (SUR) and Reactivity Management analysis.**

* **SUR Interpretation:** Analyzed the fluctuations in Start-Up Rate caused by control rod withdrawal and boron dilution steps. Verified that momentary peaks remained within safety limits (< 0.5 dpm sustained) to prevent SCRAM.
* **Reactivity Feedback:** Evaluated the "Point of Adding Heat" and its effect on neutron flux due to negative temperature feedback.

## ⚙️ Technical Highlights
The analysis covers the following operational phases based on the simulation data:

1.  **Approach to Criticality:**
    * Withdrawal of Shutdown Bank A and Control Banks B & C.
    * Boron dilution to achieve criticality.
2.  **Thermal-Hydraulic Response:**
    * **Pressurizer (PZR):** Observed that while pressure was maintained at ~15.5 MPa via heaters/sprays, the PZR level naturally rose from 23% to 43% due to coolant expansion.
    * **Feedwater Flow:** Verified the linear correlation between the rise in thermal power (to ~150 MWth) and feedwater flow (to ~77.5 kg/s).
3.  **Safety Limits:**
    * Confirmed that the Axial Imbalance (AI) and Start-Up Rate remained within target bands throughout the transient.

## 📂 Project Report
You can view the full detailed analysis, including graphs for Nuclear Power, PZR Level, and Coolant Temperatures, in the report:
👉 **[View Full Analysis Report (PDF)](./iPWR_Startup_Transient_Analysis.pdf)**

---
### 👥 Contributors 
* **Emre Sakarya** 
* Cansu Karakoç
* Yunus Atasever
* Eren Gürel
* Selman Vicdan
