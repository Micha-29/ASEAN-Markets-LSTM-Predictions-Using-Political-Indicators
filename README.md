# The Impact of Political Indicators on Asset Pricing Predictions  
*An LSTM-based Approach for ASEAN Markets*  

**Author:** Michaïl Maréchal  
**Supervisor:** M. Stam, Tilburg University  
**Degree:** BSc International Business Administration (Grade: 8.5/10, Cum Laude)  

---

## 📌 Project Overview  
This project investigates the role of **political indicators** in predicting stock index returns in **ASEAN markets** (Indonesia, Singapore, Malaysia, Philippines, and Thailand). Using a **Long Short-Term Memory (LSTM)** neural network, the study compares models with and without political indicators to determine their predictive value.  

Data spans **2000–2022**, with training (2000–2017) and testing (2018–2022) periods, enabling evaluation across different market conditions, including crises and recoveries.  

---

## ⚙️ Methodology  
- **Model:** LSTM (Long Short-Term Memory) for time series forecasting  
- **Inputs:**  
  - Political indicators from the World Bank’s Worldwide Governance Indicators (Voice & Accountability, Political Stability, Government Effectiveness, Regulatory Quality, Rule of Law, Control of Corruption)  
  - Economic indicators from the Asian Development Bank  
  - Lagged index returns (1–3 periods)  
- **Evaluation Metrics:** MSE, RMSE, MAPE  
- **Feature Importance:** Permutation Feature Importance  
- **Statistical Testing:** One-way ANOVA with Tukey’s HSD  

---

## 📊 Key Findings  
- Including political indicators significantly improved predictive accuracy:  
- Most influential political indicators: **Political Stability, Control of Corruption, Government Effectiveness**.  
- **Country differences:** Thailand and Indonesia showed the highest sensitivity to political factors, reflecting their turbulent political histories.  
- Results highlight the importance of governance and political stability for **financial market performance** in emerging economies.  

---

## 🛠 Tech Stack  
- **Languages & Libraries:** Python, TensorFlow/Keras, pandas, NumPy, scikit-learn  
- **Data Sources:**  
  - World Bank – Worldwide Governance Indicators  
  - Asian Development Bank – Key Indicators Database  
  - Wharton Research Data Services – Monthly World Indices  

---

## 📈 Results Visualization  
- Model performance comparison (with vs. without political indicators)  
- Permutation feature importance for governance indicators  
- Country-level sensitivity analysis (Thailand & Indonesia stand out)  

---

## 📜 Citation  
If referencing this work, please cite as:  

*Michaïl Maréchal (2024). The Impact of Political Indicators on Asset Pricing Predictions: An LSTM-based Approach for ASEAN Markets. BSc Dissertation, Tilburg University. Supervised by M. Stam.*  
