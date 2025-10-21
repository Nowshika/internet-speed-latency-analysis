# 🌐 Internet Speed & Latency Analysis

**Author:** Nowshika Mirza. R  
**Dataset:** [Internet Speed Dataset on Kaggle](https://www.kaggle.com/datasets/getanmolgupta01/internet-speed)  
**Goal:** Analyze and visualize global Internet performance trends through speed and latency analysis to support **SDG 9 (Industry, Innovation, and Infrastructure)**.

---

## 📊 Overview

This project performs **data analysis and visualization** on global Internet speed metrics, focusing on:
- Ping latency distribution
- Download vs Upload correlation
- Outlier detection (boxplots & z-scores)
- Time-based latency trends
- Geographic comparison (country-wise)
- Correlation heatmap between key metrics

---

## 🧠 Key Insights
- **Ping latency** distribution reveals network performance variations.
- **Download and upload speeds** are moderately correlated.
- **Latency spikes** detected using statistical anomaly detection.
- **Daily time series trends** show network congestion patterns.
- **Geographic variations** highlight regional connectivity gaps.

---

## 🧩 Tech Stack
- **Python 3**
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`

---

## 🚀 How to Run

```bash
# 1. Clone repo
git clone https://github.com/<your-username>/internet-speed-latency-analysis.git
cd internet-speed-latency-analysis

# 2. Install dependencies
pip install -r requirements.txt

# 3. Place dataset
# Download from Kaggle and rename as Internet_speed.csv

# 4. Run script
python analysis.py
