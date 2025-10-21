# 🏆 FPL Statistics Analysis

## 📘 Project Overview
This project explores Fantasy Premier League (FPL) player statistics to uncover insights that help managers make smarter team selections. Using data-driven techniques, the analysis identifies high-performing players, value picks, and trends that influence weekly performance in FPL.

## 🎯 Objectives
- Analyze the relationship between player **cost** and **points per game**.  
- Evaluate **form**, **creativity**, **influence**, and **threat** metrics to determine the best-performing players.  
- Identify **undervalued players** providing high returns for their price.  
- Visualize performance trends across different positions and teams.

## 📊 Dataset Description
The dataset contains detailed statistics for Premier League players, including:  

| Column | Description |
|--------|--------------|
| `ownership (%)` | Percentage of FPL managers owning the player |
| `cost (£m)` | Player cost in millions |
| `form` | Recent performance form (weighted metric) |
| `points per game` | Average points scored per match |
| `influence`, `creativity`, `threat` | Key FPL metrics indicating a player’s impact on the pitch |
| `total points`, `minutes`, `ICT index` | Overall season performance indicators |

The dataset includes around **745 player records** and **37 statistical columns**.

## 🧠 Analysis Steps
1. **Data Cleaning & Preparation:** Handled missing values and converted numeric columns stored as objects.  
2. **Descriptive Statistics:** Summarized player averages, medians, and distributions.  
3. **Correlation & Feature Comparison:** Explored relationships between metrics (e.g., cost vs. points).  
4. **Top Player Insights:** Ranked players by efficiency and overall points.  
5. **Visualizations:** Used Plotly and Matplotlib to display top performers and cost-effectiveness plots.

## 🧰 Tools & Technologies
- **Python (pandas, numpy, plotly, matplotlib, seaborn)**  
- **Jupyter Notebook** for exploration and visual storytelling  
- **GitHub** for project version control and portfolio sharing  

## 💡 Key Insights
- Certain mid-priced players outperform premium options when comparing **points per £m**.  
- High “form” doesn’t always translate to consistent points—player rotation and fixtures matter.  
- ICT (Influence, Creativity, Threat) metrics serve as strong predictors for upcoming form.  

## 🚀 How to Reproduce
1. Clone this repository:
   ```bash
   git clone https://github.com/Dami-lare/Data-Analysis-Projects.git
