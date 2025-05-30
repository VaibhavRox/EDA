# Online Retail EDA
------------------------------------------------------------------------------------------------

This project is an exploratory data analysis (EDA) on an online retail dataset. 
It focuses on understanding customer purchasing behavior and uncovering business insights using feature engineering, RFM analysis, and visualizations.
What’s Inside

- ✅ Data cleaning and preprocessing  
- 📊 Feature engineering (e.g., `TotalAmount`, `InvoiceMonth`)  
- 📈 RFM (Recency, Frequency, Monetary) customer segmentation    
- 📉 Visualizations for trends and customer insights  

 Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Google Colab

## 📁 File

- `online_retail_eda.ipynb` — Full Colab notebook with code and visualizations

---

Feel free to fork or download. Feedback and contributions are welcome!
#  IPL Auction 2023 - Exploratory Data Analysis (EDA)
---------------------------------------------------------------------------------------------------
IPL AUCTION 2023 EDA
This project presents a detailed exploratory data analysis of the **IPL Auction 2023** dataset. The goal was to understand player auction dynamics, franchise spending behavior, and uncover meaningful insights using data cleaning, feature engineering, and visualization.

---

## 📁 Dataset Overview

The dataset contains information about players who participated in the IPL 2023 auction, including:

- `name`: Player's name
- `player style`: Type (Batsman, Bowler, All-Rounder, Wicket-Keeper)
- `nationality`: Country of the player
- `base price (in lacs)`: Minimum price set by the player
- `final price (in lacs)`: Auctioned price (if sold/retained)
- `franchise`: The team that bought or retained the player
- `status`: Sold, Unsold, or Retained

---

## 🧹 Data Cleaning

- Handled missing values in `base price`, `final price`, and `franchise`
- Filled missing `final price` and `franchise` with "Unsold" where appropriate
- Added a new categorical column `status_encoded` with:
  - `0` → Unsold
  - `1` → Sold
  - `2` → Retained

---

## 🛠️ Feature Engineering

- `price_difference`: Difference between final and base price
  - Set to 0 for unsold or retained players
- `status_encoded`: Numerical encoding of player status
- `player_type`: Classified players as `Native` (India) or `Overseas` based on nationality

---

## 📊 Visualizations & Insights

- **Top 5 players by price difference**: Identified most profitable auction picks
- **Retained players by franchise**: Bar chart showing number of retained players per team
- **Pie chart** of player distribution: Sold vs Unsold vs Retained
- **Franchise spending**: Total amount spent by each franchise on sold players
- **Overseas vs Native players**: Pie chart and franchise-wise stacked bar chart

---


## 💻 Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook

---

## 📂 Files Included

- `IPL_AUCTION_2023_EDA.ipynb` - Complete analysis notebook
- `README.md` - Project documentation

---

## 🏁 Conclusion

This EDA provides a comprehensive overview of the IPL 2023 auction with player trends, franchise strategies, and data-driven insights. This project serves as a base for predictive modeling or deeper cricket analytics.

---
