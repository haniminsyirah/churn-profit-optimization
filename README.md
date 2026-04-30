# 📊 Churn Prediction to Profit Optimization

Most churn projects focus on predicting who will leave.  
This project goes further by answering a more important question:

👉 **Which customers are actually worth saving?**

---

## 🚀 Project Overview

Using a Telco dataset (7,000+ customers), this project combines machine learning with business strategy to transform churn prediction into **profit-driven decision making**.

Instead of targeting all high-risk customers, this approach prioritizes **high-value, high-risk segments** to maximize ROI.

---

## 🧠 Key Insight

A very small group of customers drives most of the recoverable revenue.

- Only **20 customers (~0.3%)** were selected for targeting
- Yet this segment delivered the **highest return on investment**

---

## ⚙️ Methodology

### 1. Churn Prediction
- Model: CatBoost
- Output: Churn Probability per customer

---

### 2. Business Impact Modeling

Churn probability on its own doesn’t tell the full story.

To make it more meaningful, I combined it with customer value:

Priority Score = Churn Probability × Monthly Charges

This gives a clearer picture of revenue at risk and helps prioritize high-impact customers instead of treating everyone the same.

---

### 3. Customer Segmentation

Customers were segmented based on both churn risk and customer value:

- **High Value + High Risk (Target Segment):** Priority customers for retention campaigns  
- **Low Value + High Risk:** High churn likelihood but lower business impact  
- **High Value + Low Risk:** Loyal and valuable customers (retention focus not required)  
- **Low Value + Low Risk:** Stable but low-impact customers  

---

### 4. Strategy Design
Two retention strategies were tested:

#### ❌ Mass Campaign (Baseline)
- Targets all high-risk customers
- High cost due to unnecessary incentives

#### ✅ Precision Strategy (Optimized)
- Targets only high-value, high-risk customers
- Focused and cost-efficient approach

---

## 📊 Results

| Strategy              | Target Customers | Net Profit | ROI     |
|----------------------|----------------|-----------|---------|
| Mass Campaign        | 191            | -$1,405   | -45.73% |
| Precision Strategy   | 20             | +$200     | +99.88% |

---

## 💡 Business Impact

- Reduced campaign size by **~90%**
- Turned a **loss-making strategy into a profitable one**
- Demonstrated that **precision targeting outperforms broad campaigns**

---

## 📈 Dashboard

A Power BI dashboard was built to:
- Monitor churn risk and revenue at risk
- Identify high-value target customers
- Compare campaign performance (Mass vs Precision)

---

## 🛠 Tech Stack

- Python (Pandas, NumPy, Scikit-learn)
- SHAP (Model Explainability)
- Power BI (Dashboard & Visualization)

---

## 📌 Conclusion

This project shows that:

> Churn prediction alone is not enough.  
> Real business value comes from combining machine learning with strategic decision-making.

---

## 🔗 Future Improvements

- Incorporate Customer Lifetime Value (CLV)
- Deploy real-time scoring pipeline

---

## 👤 Author

[hanim insyirah

