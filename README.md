# 📊 A/B Testing: Facebook Ads vs Google AdWords Performance Evaluation

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange?logo=jupyter)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

This project analyzes the effectiveness of **Facebook Ads** and **Google AdWords** through A/B testing to determine which platform delivers better conversions and ROI. The analysis focuses on key marketing metrics like Clicks, Conversions, CTR, and Cost-per-Conversion using Python-based tools and statistical validation.

---

## 🚀 Objective

To identify the better-performing ad platform between Facebook and Google AdWords using data analysis, visualization, and hypothesis testing.

---

## 📂 Dataset

- **Source**: [Kaggle Link](https://www.kaggle.com/datasets/shubhamdamai/ab-testing-analysis-facebook-vs-adword)  
- **Features**:  
  - date_of_campaign          - The date of each campaign, ranging from 2021 to 2024.
  - facebook_ad_campaign      - The name of the Facebook ad campaign.
  - facebook_ad_views         - The number of people who viewed the Facebook ad.
  - facebook_ad_clicks        - The number of people who clicked the Facebook ad after viewing it.
  - facebook_ad_conversions   - The number of people who became customers after clicking the Facebook ad.
  - facebook_cost_per_ad      - The cost of running a Facebook ad in (USD).
  - facebook_ctr              - Facebook Click-Through Rate in % (CTR): (facebook_ad_clicks / facebook_ad_views) × 100
  - facebook_conversion_rate  - Facebook conversion rate in % : (facebook_ad_conversions / facebook_ad_clicks) × 100
  - facebook_cost_per_click   - Cost per click for Facebook ads: (facebook_cost_per_ad / facebook_ad_clicks)
  - adword_ad_campaign       - The name of the AdWords campaign.
  - adword_ad_views          - The number of people who viewed the AdWords ad.
  - adword_ad_clicks         - The number of people who clicked the AdWords ad after viewing it.
  - adword_ad_conversions    - The number of people who became customers after clicking the AdWords ad.
  - adword_cost_per_ad       - The cost of running an AdWords ad in (USD).
  - adword_ctr               - AdWords Click-Through Rate in % (CTR): (adword_ad_clicks / adword_ad_views) × 100
  - adword_conversion_rate   - AdWords conversion rate in %: (adword_ad_conversions / adword_ad_clicks) × 100
  - adword_cost_per_click    - Cost per click for AdWords ads:(adword_cost_per_ad / adword_ad_clicks)

---

## 🔧 Tools & Libraries Used

- **Data Handling**: `Pandas`, `NumPy`
- **Visualization**: `Matplotlib`, `Seaborn`
- **Statistical Analysis**: `Scipy`, `Statsmodels`
- **Notebook Environment**: `Jupyter Notebook`

---

## 📈 Analysis Performed

- Exploratory Data Analysis (EDA)
- Distribution and Category Analysis of Clicks and Conversions
- Conversion Rate Comparison across platforms
- Independent T-Test to assess statistical significance
- Correlation Analysis between Clicks and Conversions
- Data-driven Recommendations

---

## 📌 Key Insights

- Facebook had **30%+ higher average conversions** than Google AdWords.
- **T-Test confirmed statistical significance** (p-value < 0.05).
- Weak correlation (~0.4) between Clicks and Conversions indicates the need to optimize beyond traffic (e.g., targeting, UX).

---

## ✅ Outcome

The analysis supports a **data-driven decision to prioritize Facebook Ads** for higher ROI, as it consistently outperformed Google AdWords in conversion efficiency.

---

## 📁 Project Structure
```
├── AB Testing (Facebook Vs Adwords).ipynb
├── data/                               # Raw dataset used for the project                               
├── README.md                           # Project overview and instructions
```
