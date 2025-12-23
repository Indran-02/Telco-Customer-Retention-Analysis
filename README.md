# 📞 Telco Customer Churn Analysis & Retention Strategy
![Project Header](https://raw.githubusercontent.com/Indran-02/Telco-Customer-Retention-Analysis/main/Visualizations/Telco%20Customer%20Analysis%20Dashboard.png)

## 📌 Project Overview
This project focuses on identifying why customers are leaving a telecommunications company (**Churn Rate: 26.58%**). By analyzing a dataset of **7,043 customers**, I identified key behavioral patterns and service gaps. This repository contains the full end-to-end pipeline: from raw data cleaning in **Python** to an interactive **Power BI** dashboard.

---

## 🛠️ Tech Stack & Tools
- **Python (Pandas, Seaborn, Matplotlib):** Data auditing, cleaning, and exploratory data analysis (EDA).
- **Microsoft Excel:** Feature engineering and pivot table summaries.
- **Power BI:** Interactive data visualization and DAX measures.
- **Gamma AI:** Executive presentation for stakeholders.

---

## 📂 Repository Structure
* `Data/`: Contains the raw CSV and the final formatted Excel datasets.
* `Python Sciprts/`: Jupyter Notebook containing the data cleaning and correlation analysis.
* `Visualizations/`: Dashboard screenshots and individual charts showing key drivers of churn.
* `Reports/`: Full project documentation and technical notes.
* `Presentation/`: Executive-level slides (PDF/PPTX) summarizing the business impact.

---

## 🔍 Key Business Insights
1.  **The Support Gap:** **63% of churned internet users** did not have Technical Support. Providing support is the #1 way to increase loyalty.
2.  **Fiber Optic Risk:** Despite being a premium service, Fiber Optic has a **41.89% churn rate**, likely due to high costs ($74.40 avg) without bundled support.
3.  **Contract Maturity:** Customers on **Month-to-Month** contracts represent the highest attrition risk. Long-term (1-2 year) contracts significantly stabilize revenue.

---

## 📊 Dashboard Preview
*The dashboard allows users to filter by Payment Method, Internet Service, and Tenure to identify "at-risk" customer segments in real-time.*

![Dashboard Screenshot](https://raw.githubusercontent.com/Indran-02/Telco-Customer-Retention-Analysis/main/Visualizations/Telco%20Customer%20Analysis%20Dashboard.png)

---

## 🚀 Strategic Recommendations
* **Contract Migration:** Offer a 10% discount to transition high-risk Month-to-Month users to 1-year plans.
* **Support Bundling:** Include "Premium Tech Support" for all Fiber Optic plans to reduce service frustration.
* **Retention Milestones:** Implement automated check-ins for new customers at the **3-month and 6-month marks**, as these are the peak churn windows.

---

## 📄 How to Explore
1.  Read the `Reports/Telco customer analysis documentation.docx` for the full methodology.
2.  Open `Python Sciprts/analysis.ipynb` to see the data cleaning code.
3.  View `Presentation/Telco-Customer-Churn-Analysis.pdf` for the executive summary.
