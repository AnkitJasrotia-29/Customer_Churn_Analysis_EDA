# 📉 Customer Churn Analysis: Telecom Customer Retention Insights

An exploratory data analysis (EDA) of 7,043 telecom customers to understand who is leaving, why they leave, and where retention efforts should be focused.

---

## 📝 Short Description / Purpose

This project analyses customer churn in a telecom company using demographic, account, service, and billing data. It identifies the factors most strongly linked to churn, such as tenure, contract type, internet service, add-on services, senior-citizen status, and payment method. The findings are turned into practical retention recommendations for business and customer-success teams.

---

## 🛠️ Tech Stack

- 🐍 **Python**: main language used for analysis
- 📓 **Jupyter Notebook**: interactive environment for EDA
- 🐼 **Pandas & NumPy**: data cleaning and manipulation
- 📊 **Matplotlib & Seaborn**: data visualisation
- 📄 **PDF**: executive summary of findings

---

## 🗂️ Data Source

Telecom customer dataset with **7,043 customers**. The target variable is `Churn` (Yes/No). Features include:

- **Demographics:** gender, senior-citizen status
- **Account details:** tenure, contract type, payment method
- **Services:** phone service, multiple lines, internet service, online security, online backup, device protection, tech support, streaming TV, streaming movies

---

## ✨ Features / Highlights

### 🔴 Business Problem
About **1 in 4 customers** has discontinued the service. Without knowing which customers are at risk and why, retention budgets are spread thinly and inefficiently.

Key questions:
- Which customer segments churn the most?
- When in the customer journey does churn happen?
- Which contracts, services, and payment methods are linked to churn?

### 🎯 Goal of the Analysis
- Measure the overall churn rate.
- Identify the main drivers of churn.
- Build a high-risk customer profile.
- Recommend a targeted retention strategy.

### 🔍 Walkthrough of Key Findings

| Area | Finding |
|---|---|
| **Overall churn** | 1,869 of 7,043 customers churned (**26.54%**); 5,174 (73.46%) stayed |
| **Gender** | Similar churn for males and females, so not a strong predictor |
| **Senior citizens** | **~41.7%** churn vs **~23.6%** for non-seniors (≈ 18-point gap) |
| **Tenure** | Customers with only 1–2 months of tenure churn at **~40%** |
| **Contract type** | Month-to-month customers make up **~70% of churned customers** |
| **Internet service** | Fiber optic **~40%**, DSL **~20%**, No internet **< 10%** |
| **Add-on services** | **~40%** churn without Online Security, Online Backup, Device Protection, or Tech Support vs **~15–25%** with them |
| **Streaming services** | Similar churn (~30%) across groups, so a weak indicator |
| **Phone / Multiple lines** | Similar churn across groups, so a weak indicator |
| **Payment method** | Electronic check customers show higher churn |

> ⚠️ **Note:** The ~70% figure is the share of churned customers who were on month-to-month plans. It does **not** mean 70% of all month-to-month customers churn.

### 🚨 High-Risk Customer Profile
Customers with several of these traits are priority retention targets:

- Senior citizen
- Very low tenure (new customer)
- Month-to-month contract
- Fiber optic internet service
- No Online Security, Tech Support, Online Backup, or Device Protection
- Electronic check payment

### 💼 Business Impact & Insights
- **Onboarding:** Focus on the first 1–2 months to reduce early-stage churn.
- **Contract strategy:** Move month-to-month customers to longer plans with loyalty rewards and discounts.
- **Product:** Investigate fiber optic churn across pricing, service quality, technical issues, and support.
- **Cross-sell:** Bundle protection and support services to raise perceived value.
- **Segmentation:** Group customers into low-, medium-, and high-risk segments and prioritise campaigns.

---

## ✅ Results & Conclusion

The analysis shows an overall churn rate of **26.54%**, a significant retention challenge. The strongest churn patterns are linked to:

1. Early customer tenure
2. Month-to-month contracts
3. Senior-citizen customers
4. Fiber optic internet service
5. Lack of additional support and protection services
6. Electronic check payment

Gender, streaming services, phone service, and multiple lines show comparatively weaker differences in churn.

### Key Recommendations

1. **Focus on new customers:** improve onboarding and run proactive satisfaction checks in the first 1–2 months.
2. **Promote long-term contracts:** use loyalty benefits, discounts, and bundled offers.
3. **Target senior citizens:** offer simple communication, reliable support, and suitable packages.
4. **Investigate fiber optic churn:** review service quality, pricing, technical issues, and support.
5. **Promote additional services:** bundle Online Security, Tech Support, Online Backup, and Device Protection with internet plans.
6. **Monitor payment behaviour:** keep electronic check customers under closer churn-risk monitoring.
7. **Build risk segments:** create low-, medium-, and high-risk groups and prioritise those with multiple risk traits.

**Final takeaway:** churn is best reduced through a targeted, segment-based retention strategy rather than a one-size-fits-all approach. Improving the early customer experience, encouraging long-term contracts, strengthening fiber customer satisfaction, and increasing adoption of support and protection services can all help improve long-term retention.

---

## 👤 Author & Contact

**Ankit Jasrotia**

- 💼 LinkedIn: [linkedin.com/in/ankit-jasrotia-245b0937b](https://www.linkedin.com/in/ankit-jasrotia-245b0937b)
- 🐙 GitHub: [github.com/AnkitJasrotia-29](https://github.com/AnkitJasrotia-29)
- 📧 Email: [ankitjasrotia767@gmail.com](mailto:ankitjasrotia767@gmail.com)

⭐ If you found this project useful, please consider giving it a star!
