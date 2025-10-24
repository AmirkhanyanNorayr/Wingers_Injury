# Wingers_Injury
# ⚽ Football Injury Analysis — Predicting Long-Term Durability

**Author:** Norayr  
**Date:** October 2025  
**Tools:** Python (pandas, matplotlib, seaborn, rich)

---

## 🎯 Overview
This project explores whether early career workload (matches before age 22) affects long-term durability and injury risk among elite 21st-century wingers.

All data was **manually collected from Transfermarkt** and analyzed in Python.  
Visuals were created to show trends across 15 players, including Messi, Ronaldo, Neymar, Hazard, and others.

---

## 📊 Key Visuals

### 1. Match Distribution: Before vs After 22
![Match Distribution](visuals/match_distribution.png)

### 2. Injury Growth: Before vs After 22
![Injury Growth](visuals/injury_growth.png)

### 3. Workload vs Durability
![Workload vs Durability](visuals/workload_vs_durability_labeled.png)

### 4. Correlation Matrix
![Correlation Matrix](visuals/correlation_heatmap_styled.png)

### 5. Best of the Best — Messi vs Ronaldo
![Radar Chart](visuals/radar_messi_vs_ronaldo.png)

### 6. Lamine Yamal Durability Projection
![Lamine Yamal Projection](visuals/visual6_lamine_projection.png)

---

## 🧠 Key Insights
- Wingers experience a **4–5× increase** in injuries after age 22.  
- Strong correlation between post-22 injuries and missed days (**r ≈ 0.87**).  
- Ronaldo and Salah show remarkable durability despite high workloads.  
- Yamal’s projection suggests careful load management is essential.

---

## 📄 Full Report
📘 [Football_Injury_Analysis_Report.pdf](Football_Injury_Analysis_Report.pdf)

---

## 🛠️ How to Run
```bash
git clone https://github.com/YOURUSERNAME/Wingers_Injury.git
cd Wingers_Injury
pip install pandas matplotlib seaborn rich
python Analysis.py
python lamine_visual.py
