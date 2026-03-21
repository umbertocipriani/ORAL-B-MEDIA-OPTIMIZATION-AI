# Geo-Analytics & AI Assistant: Oral-B Italy 2026 Strategy
**Role:** Lead Data Strategist & AI Architect

## 🎯 Project Overview
This project focuses on the strategic optimization of a **€100,000 media budget** for the Oral-B 2026 Dentifrice Campaign. The objective was to solve for **Peak Monthly Visibility** (Effectiveness) while maintaining strict budget **Efficiency**.

## 🛠️ Technical Implementation

### 1. Data Engineering & Geo-Analytics (KNIME)
I architected a data pipeline to merge brand performance datasets with Italian store geographic data. 

![image alt](https://github.com/umbertocipriani/ORAL-B-MEDIA-OPTIMIZATION-AI/blob/26f1926b32694d32dc9d37a6fa69063e5ed2f0ed/Screenshot%202026-03-14%20134942.png)
* **Algorithm Selection:** Tested multiple models and selected **Random Forest** for its superior performance in handling non-linear geographic variables.

### 2. Mathematical Optimization (Excel Solver)
Using **Linear Programming**, I built a model to distribute **1,143 total GRPs** across the 12-month calendar.



* **Constraints:** Monthly saturation cap (≤ 300 GRPs) and total budget (≤ €100,000).

### 3. Efficiency & Seasonality Analysis
The model identified "Efficiency Windows"—months with a Cost Index below 1.0 (Feb/Oct)—and balanced them against high-visibility months (July/Sept).

![image alt](https://github.com/umbertocipriani/ORAL-B-MEDIA-OPTIMIZATION-AI/blob/dbd50f9716807e71e82df57b452b4960b8ddba4a/Screenshot%202026-03-15%20191802.png)

### 4. Generative AI Interface (Langflow)
To make findings accessible to stakeholders, I developed an **AI Assistant** (`_Chatbot OralB AI Assistant.json`). 
* **Capability:** Enables natural language querying of the 2026 media plan.

![image alt](https://github.com/umbertocipriani/ORAL-B-MEDIA-OPTIMIZATION-AI/blob/b7e09fc3af3fce661a6b00b0cf4c52644c909c8f/Screenshot%202026-03-14%20190623.png)

![image alt](https://github.com/umbertocipriani/ORAL-B-MEDIA-OPTIMIZATION-AI/blob/a97013ca1640b8a85cff151ebe67a8af4eec69bf/Screenshot%202026-03-14%20190544.png)
![image alt](https://github.com/umbertocipriani/ORAL-B-MEDIA-OPTIMIZATION-AI/blob/04963392134568f94658f06111a3124e9a997ba7/Screenshot%202026-03-15%20191904.png)
## 📈 Strategic Impact
* **Total Visibility Score:** 1,143.33 units.
* **Result:** Achieved an optimized balance between Reach and Efficiency.

---
**Disclaimer:** This project was developed for academic purposes. All datasets have been sanitized or use proxy values to protect proprietary information.
