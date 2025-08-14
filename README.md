End-to-End Power BI Project – Loan Default Risk Analysis

📌 Project Overview
This end-to-end **Power BI** project analyses **loan default patterns** to identify the key risk factors affecting repayment behaviour.  
By segmenting borrowers based on employment type, credit score, age group, loan purpose, and education level, the dashboard enables financial institutions to **minimise defaults, optimise lending policies, and strengthen risk management**.

---

🎯 Goal / Purpose
- Analyse historical loan performance data to uncover **default trends**.
- Identify **high-risk borrower groups**.
- Provide **data-driven recommendations** to reduce losses and improve lending efficiency.

---

🌐 Data Source
Dataset inspired by a public loan default dataset:  
🔗 [Kaggle – Loan Default Prediction Dataset](https://www.kaggle.com/datasets/nikhil1e9/loan-default)  
Includes borrower demographics, loan details, credit scores, and loan performance data.

---

🛠 Tools & Technologies Used
- **Power BI** – Data loading, transformation, modelling, and visualisation
- **DAX** – Calculated measures for KPIs such as default rates and YOY changes
- **Power Query** – Data cleaning and transformation
- **Sql** – Data cleaning and transformation

---

🔍 Project Steps
1. **Data Cleaning**
- Loaded raw CSV data into Power BI.
- Handled missing values and formatted data types.
- Categorised:
  - **Credit Scores**: Very Low, Low, Medium, High
  - **Age Groups**: Teen, Adult, Senior
- Created calculated columns for:
  - **Default Rate**
  - **YOY Loan Amount Change**
  - **YOY Default Change**

2. **Visualization**
- Interactive bar charts for **Default Rate by Employment Type**
- Line graphs for **YOY Loan & Default Changes**
- Matrix views for **Loan Amount by Purpose, Credit Score, Age Group**

3. **Analysis**
- Correlation checks between **loan defaults** and variables like **employment type, credit score, education**.
- Segmentation by year to detect default spikes and anomalies.

---

📊 Key Insights
- **Employment Type**: Unemployed borrowers have the highest default rate (3.39%), followed by part-time (3.01%). Full-time workers have the lowest (2.36%).
- **Loan Purpose**: Loan amounts are evenly distributed (~6500M each across Home, Business, Education, Auto, and Other).
- **Yearly Trends**: Defaults peaked in 2015 (11.75%) and dipped in 2016 (-2.8% YOY).
- **Credit Scores**: Higher credit scores correlate with slightly higher loan amounts, but defaults are more common in low-credit categories.
- **Education**: Bachelor's degree holders (64,366 loans) slightly lead in volume over PhD holders (63,903), indicating potential targeting opportunities.

---

📌 Dashboards
**Main Pages**:
1. **Loan Overview** – Loan amounts, default rates, and borrower segmentation.
2. **Demographics & Credit Profiles** – Credit score categories, marital status, and education analysis.
3. **YOY Trends** – Annual changes in loans and defaults with comparison filters.

![image link](https://github.com/Gitrohinihub/Loan_Default-project/blob/c3c86449e23e2263c9a72747faee4c11db7faf83/Loan%20Default%20Overview.png)
![image link](https://github.com/Gitrohinihub/Loan_Default-project/blob/c3c86449e23e2263c9a72747faee4c11db7faf83/Applicant%20Demographics%20%26%20Financial%20Profile%20.png)
![image link](https://github.com/Gitrohinihub/Loan_Default-project/blob/c3c86449e23e2263c9a72747faee4c11db7faf83/Financial%20Risk%20Metrics.png)

Powerbi App : - **Interactive Dashboard** – [View Power BI App Link](https://app.powerbi.com/links/hezArLm8WE?ctid=c9b30289-5c60-41dc-85c2-d8862dea8925&pbi_source=linkShare)

---

💡 Business Recommendations
1. **Target Low-Risk Segments**  
   - Prioritise full-time employed and high-credit applicants to lower defaults by ~1% overall.
2. **Stricter Checks for High-Risk Groups**  
   - Apply tighter approval processes for unemployed or low-credit borrowers.
3. **Monitor YOY Volatility**  
   - Review YOY spikes quarterly to adjust lending caps and interest rates.
4. **Education-Based Targeting**  
   - Expand offerings to Bachelor’s and PhD holders for more stable repayments.
5. **Diversify Loan Purposes**  
   - Balance high-risk purposes with low-risk ones to stabilise revenue streams.

---

🔄 Before vs After Impact
| **Before** | **After** |
|------------|-----------|
| No segmentation by employment type or credit score | Clear borrower segmentation (e.g., unemployed default rate: 3.39%) |
| ~11–12% annual losses from defaults | Potential 10–15% reduction in defaults with targeted lending policies |
| YOY trends buried in raw data | Visual trends enable proactive adjustments |
| One-size-fits-all lending policies | Customised lending strategies by borrower profile |

---

📫 CONTACT

-GitHub: [Gitrohinihub](https://github.com/Gitrohinihub)

-LinkedIn : [Rohini Singh](https://www.linkedin.com/in/rohini-singh-8a97a1229)

-Email: miss.rohini09coder@gmail.com

