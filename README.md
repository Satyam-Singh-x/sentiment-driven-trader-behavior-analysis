# Sentiment-Driven Trader Behavior Analysis


## Overview

This project analyzes how market sentiment (Fear vs Greed) impacts trader performance and behavior using historical trade data combined with a Fear–Greed sentiment index. The analysis focuses on performance metrics, behavioral patterns, and actionable trading insights, with an additional bonus predictive modeling component.

---

## Dataset

- **Trade data:** Trade-level records aggregated to trader-day level
  
- **Sentiment data:** Daily Fear–Greed index  

Key features include daily PnL, trade frequency, long–short ratio, and extreme loss indicators.

---



## Methodology

 Cleaned and standardized timestamps across datasets
 
 Aggregated trade data at a trader-day level


  Merged daily market sentiment with trader behavior  

  
 Engineered behavioral metrics:
 
   Daily PnL
   
   Trade frequency
   
   Long–short ratio
   
   Drawdown proxy (extreme loss days)
    
 Conducted sentiment-based comparisons (Fear vs Greed)
 
 Segmented traders by activity and consistency
 
 Built a lightweight predictive model for next-day profitability (bonus)
 

---

## Key Insights

- **Fear days exhibit worse performance:** Higher downside risk and more frequent extreme losses compared to Greed days.
  
- **Behavior becomes reactive during Fear:** Higher trade frequency combined with weaker directional conviction.
  
- **Frequent traders face higher volatility:** Overtrading during Fear amplifies risk.
  
- **Predictive signal exists:** Sentiment and behavioral features provide limited but meaningful signal for next-day outcomes.
- 

---

## Strategy Recommendations

 **Reduce trading activity during Fear periods** to avoid reactive overtrading and drawdowns.
 
 **Adopt focused, conviction-driven trades during Greed periods** to better capture upside potential.
 

---

## Bonus: Predictive Model

A class-weighted logistic regression model was trained to predict next-day trader profitability using:

- Market sentiment
  
- Trade frequency
  
- Directional bias



The model demonstrates balanced performance and improved detection of loss-prone days, highlighting its usefulness as a risk-awareness tool rather than a production trading system.

---

## How to Run

1. Clone the repository:
   
   git clone https://github.com/Satyam-Singh-x/sentiment-driven-trader-behavior-analysis.git
