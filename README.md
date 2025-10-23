**Disclaimer**:  Some parts of this thesis may be inaccurate as I hadn't been corrected by a professional

📈 Thesis – Predictive Power of Market PER Levels

This project investigates whether the **Price-to-Earnings Ratio (PER)** at the beginning of a year can predict the **expected market returns** for the following year.  
Using more than **30 years of CAC40 data (70+ firms, 135 variables)**, this study evaluates the relationship between market valuation levels and subsequent performance through multiple econometric frameworks.
This project was conducted as part of a **Master’s thesis** in Financial Engineering and Quantitative Finance. 

## ⚙️ Repository Structure

📁 thesis-PER-predictability/
┣ 📓 Regression_memoire.ipynb ← Main notebook with data cleaning, regressions, and results
┣ 📊 Data_kaggle_MF/ ← Historical CAC40 dataset and derived variables
┣ 📈 MFE_Bures_Dellon/ ← Explanation, Regression tables, summary statistics, and charts
┗ 📄 README.md ← This documentation

## 🧠 Methodology

1. **Data Collection**
   - Historical CAC40 data spanning over 30 years.  
   - Variables include earnings, prices, PER ratios, and annual returns.  

2. **Data Preparation**
   - Winsorization and filtering to remove extreme values.  
   - Normalization of earnings and market capitalization for cross-sectional consistency.  

3. **Econometric Models**
   - **OLS regressions** on yearly returns as a function of PER.  
   - **Panel data estimations** to capture firm and time fixed effects.  
   - **Cross-sectional analysis** of high vs. low PER groups.  

4. **Validation**
   - Statistical tests on coefficient significance (t-stats, p-values).  
   - R² and adjusted R² for explanatory power.  
   - Visual analysis of residuals and regression fit.

## 📊 Key Findings (Summary)

- **Negative relationship** observed between PER levels and subsequent returns, consistent with valuation mean reversion theory.  
- High-PER markets tend to exhibit **lower forward returns**, while low-PER markets display **outperformance** over the following year.  
- Predictive power remains **moderate but statistically significant** in several model specifications.  

*(Full details and regression outputs available in MFE_Bures_Dellon.)*

## 🧰 Technologies

- **Python 3.12**
- Libraries: Pandas, Statsmodels, Matplotlib, Seaborn, Numpy
- Environment: Jupyter Notebook (Kaggle) / VS Code

## 📬 Author

**Thomas Bures**  
MSc Financial Engineering & Quantitative Finance  

🔗 [LinkedIn](https://www.linkedin.com/in/thomas-bures-07437b253/)  
🔗 [GitHub](https://github.com/ThomasBuresQuant)

**Leon Dellon**
MSc Financial Engineering & Quantitative Finance 

🔗 [LinkedIn](https://www.linkedin.com/in/l%C3%A9on-dellon-546bbb249/)  
