📊 Customer Churn Analysis — Power BI Dashboard

An interactive Power BI dashboard that analyzes customer churn for a telecom company: who leaves, why they leave, and which customer segments carry the highest risk.



 🎯 Project Goal

Customer acquisition is far more expensive than retention. The goal of this project is to:

- Measure the overall churn level and its business impact
- Identify the demographic, geographic, account and service factors linked to churn
- Understand the main reasons customers leave
- Give decision-makers a clear, filterable view to target retention efforts

---------------------------------------------------------------------------------------------------

 📌 Key Metrics

| Metric | Value |
|---|---|
| Total customers | **6,418** |
| New joiners | **411** |
| Total churned customers | **1,732** |
| Churn rate | **27.0%** |

--------------------------------------------------------------------------------------------------

## 🧭 Dashboard Structure

The report is organized into four analytical sections:

**1. Demographic**
- Total churn by gender
- Total customers and churn rate by age group

**2. Account Info**
- Churn rate by payment method
- Churn rate by contract type
- Total customers and churn rate by tenure group

**3. Geographic**
- Churn rate by state (top 5)

**4. Services & Churn Distribution**
- Churn rate by internet type
- Churn by individual services (usage split among customers)
- Total churn by churn category (reason for leaving)

**Interactive filters:** Monthly charge range, Marital status

-------------------------------------------------------------------------------------------------

🔍 Key Insights

**Contract type is the strongest churn driver**
- Month-to-month customers churn at **46.5%**, compared with **11.0%** for one-year and only **2.7%** for two-year contracts.

**Competitors are the #1 reason for leaving**
- **761** customers left for a competitor, far ahead of attitude (301), dissatisfaction (300), price (196) and other reasons (174).

**Fiber optic users are at the highest risk**
- Fiber optic churn rate is **41.1%**, versus 25.7% for cable, 19.4% for DSL and 7.8% for customers without internet. This points to a possible service quality or pricing issue with the fiber product.

**Payment method matters**
- Mailed check (**37.8%**) and bank withdrawal (**34.4%**) customers churn much more than credit card users (**14.8%**).

**Older customers churn more**
- Customers over 50 have the highest churn rate (**31.0%**), and this is also the largest age group (~2.8K customers).

**Strong regional differences**
- Jammu & Kashmir has the highest churn rate (**57.2%**), followed by Assam (38.1%), Jharkhand (34.5%), Chhattisgarh (30.5%) and Delhi (29.9%).

**Gender**
- Female customers account for about **64%** of churned customers (1,111 vs 621).

---

 💡 Recommendations

1. **Push longer contracts** by offering discounts or bonuses to month-to-month customers who switch to 1- or 2-year plans.
2. **Run a competitor analysis** to understand what rivals offer better (devices, speed, price) and build counter-offers.
3. **Investigate the fiber optic service** for quality, outages or pricing problems.
4. **Encourage automatic credit card payments** through small incentives.
5. **Launch targeted retention campaigns** for the 50+ age group and the high-churn states.

---

## 🛠️ Tools & Techniques

- **Power BI Desktop**: report design and visualization
- **Power Query**: data cleaning and transformation
- **DAX**: calculated measures (churn rate, total churn, new joiners, etc.)
- **Data modeling**: grouping customers into age, tenure and charge-range buckets

---

 📁 Repository Structure

```
├── Churn_Analysis.pbix      # Power BI report file
├── data/                    # Source dataset
├── images/
│   └── dashboard.png        # Dashboard screenshot
└── README.md
```

---

🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   ```
2. Open `Churn_Analysis.pbix` in **Power BI Desktop**.
3. If prompted, update the data source path to the file in the `data/` folder.
4. Use the filters at the top (Monthly Charge Range, Married) to explore different customer segments.

-----------------------------------------------------------------------------------------
👤 Author
Giorgi shengelia 
