# ORAL-B-MEDIA-OPTIMIZATION-AI
Strategic media optimization for Oral-B  using KNIME geo-analytics, linear programming (Solver), and a custom Langflow AI Assistant.
Disclaimer: This project was developed for academic purposes at Luiss University. All datasets have been sanitized, anonymized, or use proxy values to protect proprietary brand information. This repository does not contain actual confidential Procter & Gamble corporate data.
# Geo-Analytics & AI Assistant: Oral-B Italy 2026 Strategy
**Role:** Lead Data Strategist & AI Architect

## 🎯 Project Overview
This project focuses on the strategic optimization of a **€100,000 media budget** for the Oral-B 2026 Dentifrice Campaign. The objective was to solve for **Peak Monthly Visibility** (Effectiveness) while maintaining strict budget **Efficiency** and adhering to GRP (Gross Rating Point) saturation limits.

## 🛠️ Technical Implementation

### 1. Data Engineering & Geo-Analytics (KNIME)
I architected a data pipeline to merge brand performance datasets with Italian store geographic data. This allowed for the identification of under-indexed regions and high-potential geographic clusters.

KNIME Workflow
Above: The custom KNIME workflow designed for geo-segmentation and performance indexing.*

 2. Mathematical Optimization (Excel Solver)
Using Linear Programming, I built a model to distribute1,1 43 total GRPs across the 12-month calendar.
Constraints: Monthly saturation cap (≤ 300 GRPs) and total budget (≤ €100,000).
Logic: The model prioritized high-seasonality periods where the visibility-to-cost ratio was highest.

### 🤖 Algorithm Selection & Testing
To ensure the highest predictive accuracy for the 2026 campaign, I tested multiple machine learning algorithms within KNIME, including Linear Regression and Decision Trees.
* **Winner:** **Random Forest**
* **Reasoning:** Random Forest provided the best performance in handling the non-linear relationships between geographic variables and sales performance, ensuring a more robust forecast for the optimization model.


### 3. Efficiency & Seasonality Analysis
The model identified "Efficiency Windows"—months with a Cost Index below 1.0 (Feb/Oct)—and balanced them against high-visibility months (July/Sept).



### 4. Generative AI Interface (Langflow)
To make these technical findings accessible to non-technical stakeholders, I developed an **AI Assistant** (`_Chatbot OralB AI Assistant.json`). 
* **Capability:** Enables natural language querying of the 2026 media plan.
* **Stack:** Integrated logic flows designed for deployment via OpenAI APIs.

## 📈 Strategic Impact
* **Total Visibility Score:** 1,143.33 units.
* **Result:** Achieved an optimized balance between Reach and Efficiency, identifying a clear roadmap for post-summer category growth in September.

