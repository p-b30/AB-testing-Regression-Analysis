
# 📊 A/B Testing & Regression Analysis – Marketing Campaigns

## 📌 Project Overview

This project compares the performance of two advertising platforms — **Facebook Ads** and **AdWords Ads** — to determine which delivers better results in terms of **clicks, conversions, and cost-effectiveness**.

It combines **A/B testing, statistical analysis, and regression modeling** to generate actionable marketing insights.

---

## 🎯 Business Objective

* Identify the more effective advertising platform
* Optimize ROI for marketing campaigns
* Improve conversion rates and cost efficiency
* Support data-driven budget allocation

---

## ❓ Research Question

**Which ad platform performs better in terms of conversions, clicks, and cost-effectiveness?**

---

## 📂 Dataset Description

* Daily campaign data for the year **2019 (365 records)**
* Covers both **Facebook Ads** and **AdWords Ads**

### Key Features:

* Date
* Ad Views
* Ad Clicks
* Ad Conversions
* Cost per Ad
* Click-Through Rate (CTR)
* Conversion Rate
* Cost per Click (CPC)

---

## 🧹 Data Preprocessing

* Converted date column to datetime
* Cleaned percentage and currency values
* Filtered and structured campaign-specific datasets
* Prepared features for statistical and regression analysis

---

## 📊 Exploratory Data Analysis (EDA)

* Distribution analysis of clicks and conversions
* Conversion category segmentation
* Comparison of high vs low conversion days
* Scatter plots to analyze relationships

### Key Insight:

* Facebook shows **more frequent high-conversion days** compared to AdWords

---

## 🔗 Correlation Analysis

* **Facebook:** Strong positive correlation (0.87)
* **AdWords:** Moderate correlation (0.45)

👉 **Conclusion:** Clicks drive conversions much more effectively on Facebook

---

## 🧪 A/B Testing (Hypothesis Testing)

### Hypothesis:

* **H0:** Facebook ≤ AdWords conversions
* **H1:** Facebook > AdWords conversions

### Results:

* Facebook Mean Conversions: **11.74**
* AdWords Mean Conversions: **5.98**
* p-value: **~0 (statistically significant)**

👉 **Conclusion:** Facebook significantly outperforms AdWords

---

## 📈 Regression Analysis

* Model: **Linear Regression (Facebook Clicks → Conversions)**
* R² Score: **76.35%**
* Strong predictive relationship between clicks and conversions

### Example Predictions:

* 50 clicks → ~Expected conversions
* 80 clicks → Higher expected conversions

👉 Useful for **forecasting campaign performance**

---

## 📅 Time Series Insights

### Weekly Trends:

* Higher conversions on **Monday & Tuesday**

### Monthly Trends:

* Overall increasing trend
* Lower performance in some months due to seasonality

---

## 💰 Cost Analysis

### Cost Per Conversion (CPC):

* Stable overall trend
* Lowest in **May & November**
* Highest in **February**

👉 Suggests **optimal months for budget allocation**

---

## 🔄 Cointegration Analysis

* Strong long-term relationship between:

  * **Ad Spend**
  * **Conversions**

👉 Indicates stable ROI behavior over time

---

## 📊 Key Findings

* Facebook is significantly more effective than AdWords
* Strong relationship between clicks and conversions (especially Facebook)
* Certain time periods offer better ROI
* Budget allocation can be optimized using data trends

---

## ✅ Recommendations

* Increase investment in **Facebook Ads**
* Optimize AdWords strategy (targeting, creatives)
* Allocate higher budget during **low CPC months**
* Use regression model for **conversion forecasting**
* Focus campaigns early in the week for better engagement

---

## 🏁 Conclusion

This project demonstrates how **A/B testing and regression analysis** can be used to evaluate marketing performance, optimize ad spend, and improve business decision-making through data-driven insights.

---

## 🛠️ Tools & Technologies

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* SciPy (Hypothesis Testing)
* Statsmodels (Time Series & Cointegration)

---

## 📂 How to Use

1. Clone the repository
2. Add dataset (`marketing_campaign.csv`)
3. Run the notebook/script
4. Explore visualizations and insights
5. Modify parameters for further analysis

---


