# 🛒 PESTEL Analysis of the Canadian Retail Grocery Sector

## 📌 Project Overview

This project delivers a comprehensive **PESTEL analysis** (Political, Economic, Social, Technological, Environmental, and Legal) of the **Canadian retail grocery sector**, with a specific focus on **supply chain management risks and opportunities**.

Using a large-scale simulated **transactional dataset (Kaggle)** and external secondary research sources, the project integrates **data cleaning, statistical analysis, and predictive modeling** to generate actionable insights for operational decision-making.

---

## 📂 Methodology

### 🔹 Data Collection

* **Primary Data**: `new_retail_data.csv` from Kaggle

  * Customer demographics (age, gender, income, segment)
  * Transaction details (purchases, amount spent, product type, brand)
  * Temporal variables (date, month, year)
  * Technological indicators (payment & shipping methods)
* **Secondary Data**: Government agencies, industry publications, and research reports for Political, Environmental, and Legal insights.

### 🔹 Data Cleaning & Handling

* Filtered to focus on **Canadian grocery transactions** → 8,892 records → refined to **8,745 valid entries**.
* Standardized column names, removed PII & irrelevant fields.
* Converted datatypes (datetime & numeric).
* Treated missing values: dropped critical fields, imputed categorical fields with mode.
* Outlier detection via **IQR method** on purchase amounts.

---

## 📊 PESTEL Analysis Highlights

### 🏛 Political

* Food safety standards, labor laws, and trade regulations shape retail operations.
* Regional order distribution (Victoria, Winnipeg, Edmonton, Hamilton) highlights influence of **local governance and infrastructure**.

### 💰 Economic

* Seasonal sales peaks (May, July, January) linked to holidays and consumer cycles.
* Spending consistent across income groups, reflecting **baseline necessity of groceries**.

### 👥 Social

* High customer concentrations: **18–20 and 45–48 age groups**.
* No significant spending difference by gender.
* Water, juice, and soft drinks dominate purchases.

### 💻 Technological

* **Digital payments** dominate (Credit 29.5%, Debit 26.4%, PayPal 19.4%).
* Customers prefer **same-day shipping** and show strong adoption of **e-commerce**.

### 🌱 Environmental

* Packaged goods (water, juice) contribute to waste concerns.
* Sustainability pressures demand **eco-friendly packaging, sourcing, and logistics**.

### ⚖ Legal

* Compliance with **food safety, labor, and consumer protection laws** critical.
* Regional sales patterns reflect **localized legal and licensing costs**.

---

## 🔮 Predictive Modeling

* **Linear Regression**: Identified steady upward trend in sales.
* **Prophet Model**: Captured seasonal cycles (holiday peaks, post-holiday troughs).

  * MAE: \$30,738.21
  * RMSE: \$36,827.45
* **Environmental Impact Forecast**: Growth in perishable demand → requires sustainable logistics & packaging solutions.

---

## 💡 Key Insights

* Grocery sales follow **predictable seasonal cycles** → align inventory & workforce planning.
* **Demographics & product segmentation** enable tailored marketing strategies.
* **Technology adoption** (digital payments, shipping preferences) demands robust digital infrastructure.
* Environmental and legal compliance both **risks & opportunities** for resilience.

---

## ✅ Recommendations

1. **Adopt AI-driven demand forecasting** to optimize inventory & reduce waste.
2. **Invest in digital infrastructure** (secure payments, scalable e-commerce, last-mile delivery).
3. **Design segment-specific marketing strategies** aligned with demographics and income levels.
4. **Strengthen supply chain resilience** via diversification and sustainability practices.
5. **Proactive labor planning & training** to adapt workforce to seasonal demand and digital tools.

---

## 📖 References

* Government of Canada, CFIA, ESDC, Statistics Canada, Bank of Canada
* Deloitte, McKinsey, Gartner, NielsenIQ, OECD, World Bank
* Smith & Brown (2022), *Journal of Environmental Management*
* [UN Sustainable Development Goals](https://sdgs.un.org/goals)

