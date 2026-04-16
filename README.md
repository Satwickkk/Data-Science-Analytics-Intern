# Data-Science-Analytics-Intern

# Bitcoin Sentiment vs Trader Behavior Analysis

## Overview

This project analyzes how Bitcoin market sentiment (Fear vs Greed) influences trader performance and behavior. By combining sentiment data with historical trading activity, we uncover patterns and derive actionable trading strategies.

---

## Setup & How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/Satwickkk/Data-Science-Analytics-Intern.git
   ```

2. Open the notebook:

   * Use **Jupyter Notebook** or **Google Colab**

3. Upload datasets:

   * `fear_greed_index.csv`
   * `historical_data.csv`

4. Run all cells sequentially

---

## Output (Charts & Tables)

The notebook generates:

* 📈 Average PnL comparison (Fear vs Greed)
  <img width="631" height="610" alt="image" src="https://github.com/user-attachments/assets/bbf82ff5-9ef2-489e-a9c6-7859df542246" />


  
* 📉 Win rate analysis
  <img width="615" height="617" alt="image" src="https://github.com/user-attachments/assets/81bbcce5-3396-462b-9541-38f0b8a92c07" />

  
  
* 📌 Long vs Short position distribution
  <img width="633" height="616" alt="image" src="https://github.com/user-attachments/assets/057ab184-2785-4070-bcff-e824b01d4c4d" />

  
  

---

## Methodology

* Loaded and cleaned both datasets
* Handled missing values and duplicates
* Converted timestamps into a common date format
* Created key metrics:
  * Daily PnL
  * Win rate
  * Trade frequency
  * Average trade size
* Merged datasets based on date
* Performed comparative and behavioral analysis

---

## Key Insights

1. **Higher profitability during Greed**

   * Traders achieve better PnL and win rates in Greed phases.

2. **Behavior changes with sentiment**

   * Trade frequency and position sizes increase during Greed.

3. **Cautious behavior during Fear**

   * Traders reduce activity and take smaller positions.

---

## Strategy Recommendations

### 1. Dynamic Risk Adjustment

Reduce position sizes during Fear and increase exposure during Greed to balance risk and returns.

### 2. Trade Frequency Optimization

Avoid overtrading in Fear; increase participation during Greed for better opportunities.

### 3. Position Bias Strategy

Prefer long positions in Greed and adopt defensive or short strategies during Fear.

---

## Conclusion

This project demonstrates that market sentiment significantly impacts trader behavior and performance. By aligning strategies with sentiment, traders can improve decision-making and manage risks more effectively.
