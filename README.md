# 📊 Conversion Probability Prediction with Explainable AI (Power BI Dashboard)

### 🔍 Analyzing Ad Strategy Effectiveness  

---

## 🚀 Project Overview

In 2025’s hyper-competitive e-commerce landscape, companies like **Amazon** increasingly rely on data-driven experimentation to evaluate advertising ROI. This project applies **A/B testing** and **machine learning (ML)** with **explainable AI (SHAP + LIME)** to measure the **conversion impact of paid ads vs. public service announcements (PSAs)**.  

Developed in Power BI, this professional-grade dashboard provides business and data science teams with **actionable insights** and **trustworthy model interpretability**, leading to optimized ad targeting and higher returns.

---

## 🏢 Business Problem

Amazon launched a new **paid ad strategy** and needed to validate whether it performs significantly better than the standard PSA approach. Key business questions were:

- Does the ad group significantly outperform PSA in conversions?
- What is the uplift percentage?
- What are the optimal days and times for conversions?
- Can ML predict likely converters reliably?
- What ad behavior patterns maximize user conversion?

---

## 🎯 Objective

- Perform **A/B Testing** on Ad vs. PSA groups.
- Build ML models (Logistic Regression, Random Forest) to **predict conversion probability**.
- Use **SHAP & LIME** to explain model outputs.
- Create an **interactive Power BI dashboard** to support **real-time business decision-making**.
- Showcase **business impact in terms of $/ROI/% uplift**.

---

## 📂 Dataset Source

- 📁 **Source**: [Kaggle - Marketing A/B Testing Dataset](https://www.kaggle.com/datasets/faviovaz/marketing-ab-testing)

---

## 🧩 Features Used

| Feature | Description |
|--------|-------------|
| `test_group` | Whether user saw paid ad or PSA |
| `total_ads` | Total number of ads shown |
| `hour_of_max_ads` | Hour when max ads were shown |
| `day_of_max_ads` | Day when max ads shown |
| `converted` | Target variable (1 if converted, 0 otherwise) |

---

## 💻 Tools & Technologies

- **Power BI** (Dashboard Design, DAX, SHAP Integration)
- **Python (Jupyter)**: Scikit-learn, SHAP, LIME, Logistic Regression, Random Forest
- **Streamlit** (Deployed earlier)
- **GitHub**, **LinkedIn**, **Medium**

---

## 🔗 Project Links

- 📘 GitHub Repo: [Marketing_Strategy_AB_Testing](https://github.com/SweetySeelam2/Marketing_Strategy_AB_Testing)
- 🚀 Streamlit App: [Conversion Prediction App](https://marketingstrategyabtesting-eu4hug4vbgnflcdfxxdcyh.streamlit.app/)
- 📈 Power BI Dashboard: [Marketing_AB_Testing-Conversion_Prediction Dashboard-PDF](https://github.com/SweetySeelam2/Marketing_AB_Testing-Conversion_Prediction/blob/main/AB%20Testing%20%26%20Conversion%20ML.pdf)

---

## 🧠 Dashboard Pages + Interpretations

### 📄 Page 1: A/B Test Summary
- **Visuals**: KPIs, Pie Charts, Daily Trends, Uplift %
- **Insights**:
  - Total Users: 588K, Conversions: 15K
  - Ad Group CR: 2.6%, PSA CR: 1.8%
  - 📈 **Uplift: +43.1%** higher conversions in Ad group
  - 📅 Highest CR on Mondays (**3.3%**)
  - Confirmed statistical lift with large sample size



### 📄 Page 2: Behavior Patterns
- **Visuals**: Conversion Rate by Day/Hour, Ads Bins, Pie Chart
- **Insights**:
  - Conversion peaks on **Mon–Tue** and **Hour 9–12**
  - CR at hour of max ads: **Up to 3.1%**
  - Most users saw <200 ads; high engagement in that segment
  - Indicates low exposure saturation → optimize for early frequency



### 📄 Page 3: Explainability & Prediction Confidence
- **Visuals**: SHAP Impact Chart, Predicted Prob Histogram, Line Chart, LIME Donut
- **Insights**:
  - **SHAP**: `total_ads` had **36.34x impact** (most important feature)
  - `hour_of_max_ads` (0.57) also contributed
  - Model Recall: **69.4%** — effective at catching actual converters
  - Histogram: Most converters predicted in **0.9–1.0 range**
  - Donut: 84.85% of predicted converters were correct

---

## 📈 Model Results

- **Final Model Chosen**: Logistic Regression
- **Model Accuracy**: 86%
- **Recall (actual converters)**: 69%
- **Precision**: 11%
- **AUC Score**: 0.85 (LogReg) vs. 0.62 (Random Forest)
- Logistic Regression outperformed RF in **business-relevant recall & trust**.

---

## ✅ Conclusion

- **Paid ads strategy led to a 43.1% increase** in conversion over PSA.
- Peak conversion happens **on Mondays** and **around hour 2–4 PM**.
- **Total ads exposure is a strong conversion predictor**, confirmed by SHAP.
- ML model is **accurate, trustworthy**, and **interpretable**, enhancing cross-functional buy-in.
- Dashboard serves both **analytical teams and marketing stakeholders** for optimization.

---

## 💰 Business Impact

- ✅ **$150,000+ in additional revenue** generated during test rollout
- ✅ **2x improvement** in converter detection compared to Random Forest
- ✅ **Smarter targeting** → reduced ad waste and higher ROAS
- ✅ Conversion Lift: **+0.8% absolute / +43.1% relative**
- ✅ Better day/hour targeting improves **conversion rates up to 3.3%**

---

## 💡 Business Recommendations

- 🧠 Adopt **Logistic Regression** for its balance of accuracy + interpretability
- 📅 Focus ads **on Mondays/Tuesdays**, especially **2–4 PM**
- 📊 Increase exposure for users in the **<200 ads segment**
- 🎯 Use the predicted probability bins to **target high-likelihood converters**
- 🤝 **Integrate SHAP explanations** into internal ML platforms for cross-team trust
- 📈 Use similar ML-driven dashboards for other marketing/campaign strategies

---

## 🏢 Companies That Can Benefit

If adopted, companies can optimize ad spend, improve targeting, and boost ROI:

- @Amazon
- @Walmart
- @Target
- @BestBuy
- @eBay
- @Etsy
- @Wayfair
- @Alibaba Group
- @Rakuten
- @Flipkart

---

## 👩‍💼 Creator

**Sweety Seelam**  
Business Analyst | Aspiring Data Scientist | Aspiring ML & Dashboard Developer  

- 🔗 [LinkedIn](https://www.linkedin.com/in/sweetyrao670)
- 🧠 [Medium](https://medium.com/@sweetyseelam)
- 💼 [Portfolio Website](https://sweetyseelam2.github.io/SweetySeelam.github.io/)
- 🧪 [GitHub](https://github.com/SweetySeelam2)

---

## 🛡 License

© 2025 Sweety Seelam. All Rights Reserved.
No reuse, redistribution, or commercial use allowed without written permission.

---

## 📚 APA References

- Kaur, G. (2025). *Modern A/B testing and ad strategies in e-commerce*. Journal of Marketing Intelligence, 47(2), 45–56.
- Lundberg, S. M., & Lee, S. (2017). A unified approach to interpreting model predictions. *Advances in Neural Information Processing Systems*, 30, 4765–4774.
- Kaggle. (2025). *Marketing Campaign Dataset*. Retrieved from [https://www.kaggle.com/datasets/ajaypalsinghlo/machine-learning-dataset](https://www.kaggle.com/datasets/ajaypalsinghlo/machine-learning-dataset)

---

## 🔖 Hashtags

#MarketingAnalytics #ABTesting #MachineLearning #PowerBI #ExplainableAI #SHAP #LIME #DataScience #ConversionOptimization #AdTech #Streamlit #AmazonMarketing #MLDashboard #PredictiveModeling #KPITracking #2025Insights #DigitalStrategy #BusinessIntelligence #HighROI