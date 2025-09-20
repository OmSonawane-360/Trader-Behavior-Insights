# Trader Behavior Insights – Junior Data Scientist Assignment

## Author
**Om Sonawane**  
- GitHub: [github.com/YourGitHubID](https://github.com/YourGitHubID)  
- LinkedIn: [linkedin.com/in/YourLinkedInID](https://linkedin.com/in/YourLinkedInID)  
- Email: your.email@example.com  

---

## Overview
This repository contains a data science project that analyzes the relationship between **Bitcoin market sentiment** and **trader performance**. The goal is to uncover patterns in trader behavior during different market conditions and provide actionable insights for smarter trading strategies.  

Two primary datasets are used:

1. **Fear & Greed Index** – Measures Bitcoin market sentiment over time, classified as **Fear** or **Greed**.  
2. **Historical Trader Data** – Contains trade-level information including account, coin, execution price, trade size (tokens & USD), trade side (BUY/SELL), timestamps, PnL, and other details.

**Objective:** To explore how market sentiment influences trading behavior and performance, identify hidden patterns, and generate insights that can support more informed trading decisions.

**Datasets:** [Click here to access datasets on Google Drive](https://drive.google.com/drive/folders/1JChsIXU0pAnoHbSMwAz26wc_mDqRa72G?usp=drive_link)

---

## Methodology / Approach
The analysis was performed in a structured, step-by-step manner:

1. **Data Cleaning**
   - Standardized column names across datasets.  
   - Converted timestamps to proper `datetime` format.  
   - Handled missing or invalid values.  

2. **Feature Engineering**
   - Calculated **daily total PnL per account**.  
   - Flagged profitable trades for analysis.  
   - Extracted the `Date` from timestamps to merge with sentiment data.

3. **Merging Datasets**
   - Combined trader data with Fear & Greed Index on trade date.  
   - Ensured each trade is associated with the correct market sentiment.

4. **Exploratory Data Analysis (EDA)**
   - Visualized **PnL distribution** for Fear vs Greed days.  
   - Tracked **daily total PnL trends** over time.  
   - Examined **BUY vs SELL behavior** under different sentiment conditions.  
   - Optional: Explored trade size and leverage patterns (where applicable).

5. **Statistical Analysis**
   - Conducted **t-tests** to compare trader performance between Fear and Greed periods.  
   - Checked for significant differences in profitability.

6. **Visualization**
   - Used **boxplots, bar charts, and line plots** to convey key insights clearly.  
   - Created a **final visual summary/dashboard** for easy interpretation.

---

## Key Insights
- Trader performance **varies significantly with market sentiment**.  
- BUY/SELL behavior shows distinct patterns depending on Fear or Greed days.  
- Top traders tend to maintain **consistent strategies**, regardless of market sentiment.  
- Patterns in trade size, leverage, and trade frequency can be observed across different market conditions.

---

## Repository Structure
- `Trader_Behavior_Insights_Assignment.ipynb` – Complete Colab notebook with code, analysis, and visualizations.  
- `final_output.csv` – Aggregated daily PnL merged with market sentiment.  
- **Datasets:** Access via [Google Drive link](https://drive.google.com/drive/folders/1JChsIXU0pAnoHbSMwAz26wc_mDqRa72G?usp=drive_link).

---

## How to Use
1. Open the notebook in [Google Colab](https://colab.research.google.com/).  
2. Run all cells sequentially.  
3. Explore the **visualizations**, **statistical tests**, and **final insights**.  

---

## Contact
If you have any questions or would like to discuss the analysis, feel free to contact me:  

**Om Sonawane**  
- Email: your.email@example.com  
- GitHub: [github.com/YourGitHubID](https://github.com/YourGitHubID)  
- LinkedIn: [linkedin.com/in/YourLinkedInID](https://linkedin.com/in/YourLinkedInID)

---

**Note:** This project was completed as part of a **Junior Data Scientist assessment** and demonstrates skills in data cleaning, feature engineering, exploratory data analysis, statistical testing, and visualization.
