#  Trader Behavior Insights – Market Sentiment vs Profitability

**Author:** Dasari Arjun  
**Role:** Junior Data Scientist – Trader Behavior Insights  
**Date:** November 2025  

---

##  Objective
The goal of this project is to understand how trader performance changes with market emotions — Fear, Greed, and everything in between.  
By studying the relationship between **trader profit/loss data (Hyperliquid)** and the **Bitcoin Fear & Greed Index**, the project uncovers how crowd sentiment impacts risk-taking, trade size, and overall profitability.

---

## ⚙️ Approach
1. **Cleaned** both datasets and standardized date formats.  
2. **Aggregated** daily trading data to calculate metrics like total PnL, average trade size, and trade count.  
3. **Merged** trading and sentiment datasets by date to analyze correlations.  
4. **Visualized** how trader performance behaves under different sentiment phases (Fear, Greed, Neutral, etc.).  
5. **Interpreted** the results to draw behavioral and market-level insights.

---

## Datasets Used
| Dataset | Description | Key Fields |
|----------|--------------|-------------|
| Hyperliquid Trader Data | Real trade records with execution details and profit/loss values. | date, closed_pnl, size_usd |
| Bitcoin Fear & Greed Index | Daily market sentiment classification. | date, classification |

---

##  Key Insights
- Traders tend to **increase risk** and trade size during *Greed* and *Extreme Greed* phases.  
- **Profitability becomes volatile** in greedy markets — large wins and large losses both appear.  
- **Fear phases** bring smaller, more stable profits as traders become cautious.  
- Market sentiment directly influences trading confidence and behavior.

---

##  Visualizations
The analysis includes three core charts:

1. **Daily Total PnL by Market Sentiment**  
   → Shows how profits differ during Fear, Greed, and Neutral moods.  
2. **Average Trade Size by Market Sentiment**  
   → Displays how risk appetite changes with market emotion.  
3. **Daily Total PnL Over Time**  
   → Highlights emotional market cycles and volatility patterns.

All charts are available inside the `/outputs/` folder.

---

##  Tools Used
- **Python Libraries:** pandas, matplotlib, seaborn  
- **Environment:** Google Colab  
- **Version Control:** Git + GitHub  

---

---

##  Resources
-  [Colab Notebook (View Analysis)](https://colab.research.google.com/drive/1FuME5ur8VnO-KwVkdCiKY3599M89XSGR#scrollTo=SgcWO2oUDDOE) 
-  [Bitcoin Fear & Greed Index Dataset](https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing)  
-  [Historical Trader Data](https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing)

---

##  Conclusion
This project proves that trader performance is not just driven by technicals — it’s deeply influenced by **market emotion**.  
Periods of greed drive aggressive trading and volatility, while fear leads to defensive, disciplined behavior.  
Understanding this emotional rhythm can help traders and analysts design smarter, risk-aware strategies.

---

 **Author:** [Dasari Arjun](https://github.com/Arjundas08)  
 *“Analyzing emotion through data is the first step to mastering the markets.”*

