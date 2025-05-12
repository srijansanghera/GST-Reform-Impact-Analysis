# Evaluating the Impact of India's 2017 GST Reform on Government Revenue

This project investigates the impact of India's 2017 Goods and Services Tax (GST) reform on government revenue. Using a combination of **Difference-in-Differences (DiD)** and **Synthetic Control Method**, the analysis constructs a credible counterfactual to assess the causal effect of GST on India's tax collections.

## 📝 Project Overview

- **Research Question:**  
  *Did the implementation of GST in India significantly affect government revenue collection between 2017–2022?*

- **Dataset Source:**  
  Self-constructed dataset using the Bloomberg Terminal (countries: India, Brazil, South Africa, the Philippines, Thailand, Vietnam).

- **Key Variables:**
  - Government revenue (quarterly)
  - Policy rates
  - Inflation rates

- **Period of Analysis:**  
  Q1 2013 to Q4 2022.

## 🛠 Methods

- Data extraction and aggregation via Bloomberg ECST and ECWB tools.
- Standardization of variables across countries using scaling techniques.
- Application of:
  - **Difference-in-Differences (DiD)** regression.
  - **Synthetic Control Method** to construct a counterfactual India without GST reform.
- Evaluation of post-reform trends against synthetic control.

## 🔧 Technologies Used

- Bloomberg Terminal and Python 
- Libraries: `pandas`, `numpy`, `sklearn`, `statsmodels`, `matplotlib`

## 📊 Results

- Created a robust synthetic control group matching India's pre-GST revenue trends.
- Estimated the treatment effect of GST on revenue collections post-2017.
- Visualized and interpreted results to assess policy effectiveness.

## 👥 Authors

- Srijan Sanghera
- Shreya Iyer

