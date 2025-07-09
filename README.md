# 🧠 SEO Underpricing Prediction | BUSINFO 717

This project tackles the problem of predicting **underpricing in Seasoned Equity Offerings (SEOs)** using machine learning models. Our aim? Help financial analysts identify when an offering is likely to be underpriced — and more importantly, how to act on it.

---

## 📊 Business Context
Seasoned Equity Offerings (SEOs) are a common method for companies to raise capital post-IPO. However, many offerings end up underpriced, leading to significant short-term market inefficiencies — and potentially, missed opportunities.

We built a predictive pipeline using historic SEO data, market indicators (e.g., VIX), and security characteristics to spot underpriced deals in advance. Think of it as your crystal ball for financial modelling.

---

## 🔧 What We Did

- **Sourced messy SEO data** from WRDS, Yahoo Finance, and CBOE
- **Cleaned & engineered features** — 29 predictors from 116 variables
- **Defined underpricing** using offer vs. close price thresholds
- **Built classification models**: Logistic Regression, Random Forest, and LightGBM
- **Evaluated performance** using 10-fold cross-validation
- **Added explainability** with SHAP and LIME (next steps)
- **Designed monetisation and risk mitigation strategies**

> 🧪 Fun Fact: The custom risk score used to flag underpricing? That was my idea. It helped fine-tune strategy while keeping false alarms in check.

---

## 🚀 Key Insights

- **LightGBM and Random Forest outperformed** Logistic Regression, especially in non-linear patterns.
- **Lower thresholds** caught more underpriced cases — a trade-off between sensitivity and false positives.
- Model can guide **first-day trading strategies** to maximise gains.
- Future improvements include **longer-term backtesting** and **model explainability** for investor confidence.

---

## 📂 Files in This Repo

| File | Description |
|------|-------------|
| `SEO_Under_Code.ipynb` | Jupyter Notebook with data prep, modelling, and evaluation |
| `717-Group 1.pptx` | Final presentation deck with insights, visuals, and recommendations |



---
