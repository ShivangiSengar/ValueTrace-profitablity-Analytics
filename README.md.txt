# ValueTrace — Business Profitability & Leakage Analytics

## 📌 Project Overview

ValueTrace is a business profitability analysis project built around a simulated Direct-to-Consumer (D2C) company.

The business is generating significant sales, but management wants to understand why sales growth is not translating into profitable growth.

The project analyzes profitability across products, categories, customers, returns, deliveries, and marketing campaigns to identify where business value is being lost.

### Business Question

> **“Sales are growing, so why isn't profit growing? Where are we losing money?”**

---

## 🎯 Business Objectives

- Measure net sales and contribution profit
- Identify loss-making categories and products
- Analyze the impact of discounts and product costs
- Understand return-related costs
- Analyze delivery and shipping costs
- Evaluate customer profitability
- Analyze campaign performance
- Provide practical management recommendations

---

## 🛠️ Tools Used

- Microsoft Excel
- Microsoft Power BI
- DAX

---

## 📊 Dataset

The dataset is a **synthetically generated business dataset** created specifically for this portfolio project.

| Data Area | Records |
|---|---:|
| Customers | 8,000 |
| Products | 250 |
| Orders | 50,000 |
| Deliveries | 50,000 |
| Returns | 4,904 |
| Campaigns | 20 |

The order data covers **2024–2025**.

---

## 🔍 Analysis Methodology

1. Data quality audit and cleaning in Excel
2. Business metric and profitability calculations
3. Power BI data modelling
4. DAX measure development
5. Interactive dashboard creation
6. Root-cause analysis
7. Management recommendations

---

## 💰 Key Business KPIs

| KPI | Result |
|---|---:|
| Total Net Sales | ₹165.58M |
| Total Orders | 50K |
| Contribution Profit | -₹30.18M |
| Contribution Margin | -18.23% |
| Total Product Cost | ₹170.56M |
| Total Shipping Cost | ₹5.30M |
| Total Return Cost | ₹19.91M |
| Return Rate | 9.81% |

### Contribution Profit Definition

**Contribution Profit = Net Sales − Product Cost − Shipping Cost − Return Cost**

This metric was used to understand the actual business value generated after major variable costs.

---

## 📈 Dashboard Pages

### 1. Executive Overview
Provides a high-level view of sales, orders, contribution profit, costs, and category performance.

### 2. Returns & Delivery
Analyzes return rates, return reasons, return costs, delivery costs, delivery performance, and regional patterns.

### 3. Customer Economics
Analyzes customer profitability, customer segments, regional economics, and the relationship between sales and contribution profit.

### 4. Product Economics
Identifies the highest- and lowest-contributing products and compares contribution margins across categories.

### 5. Campaign Performance
Evaluates campaign-attributed sales, contribution profit, and campaign budget performance.

### 6. Management Summary & Recommendations
Summarizes the major business findings and converts the analysis into actionable recommendations.

---

## 🔎 Key Business Findings

- Total net sales reached ₹165.58M, but contribution profit was -₹30.18M, indicating that sales growth is not translating into profitable growth.
- All five categories generated negative contribution profit, showing that profitability is a business-wide issue.
- Electronics recorded the largest contribution loss at -₹11.2M, making it the highest-priority category for investigation.
- Home & Kitchen (-₹7.1M) and Fashion (-₹6.4M) were the next-largest contributors to the overall loss.
- The overall return rate is 9.81%, indicating that product returns are an important cost factor to monitor.

---

## 💡 Management Recommendations

- Prioritize Electronics for profitability improvement because it has the largest contribution loss.
- Review pricing, discount levels, and product costs across loss-making categories before increasing sales volume.
- Investigate return-related costs and identify products or categories with unusually high return rates.
- Review shipping and delivery costs to identify opportunities to reduce fulfillment expenses.
- Focus future growth on products and customer segments that generate stronger contribution profit, rather than optimizing only for sales.

---

## 📁 Project Structure

```text
ValueTrace_Profitability_Analytics/
│
├── 01 Raw Data/
├── 02 Excel Cleaning/
├── 03 POWER BI/
├── 04 Insights/
└── 05 GitHub/