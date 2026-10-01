# Olist E-Commerce Analysis 📦

A data analysis project investigating what drives late deliveries and low 
customer review scores on Olist, a Brazilian e-commerce marketplace — and 
quantifying the revenue impact of both.

## 🎯 Objective
Understand the root causes behind delivery delays and poor review scores, 
and translate those findings into actionable, revenue-focused recommendations.

## 🛠️ Tools & Libraries
- Python
- Pandas & NumPy — data cleaning, merging, and transformation
- Matplotlib & Seaborn — visualization

## 📊 Process
- Merged 8+ relational tables (orders, order items, payments, reviews, 
  customers, products, sellers, geolocation) into a unified dataset
- Performed exploratory data analysis (EDA) to identify delivery and 
  review score patterns
- Investigated correlations between delivery delays and review scores
- Quantified revenue at risk from late deliveries and low ratings
- Delivered root-cause findings with clear, actionable recommendations

## 📈 Key Findings

- **$985,819** (7.3% of total revenue) is tied to orders that arrived late; **$2,250,027** (16.6%) is tied to orders rated 1–2 stars
- **Late delivery tanks satisfaction**: on-time orders average a 4.15/5 review score — late orders drop to 2.26/5
- **Distance is the strongest driver of late delivery**: cross-state orders are late 7.6% of the time vs. 4.4% for same-state orders
- **Bulky items ship late more often**: categories like furniture and home comfort items see late rates above 13%, more than double the 6.4% platform average
- **RJ is the clearest priority**: Brazil's #2 revenue state ($1.8M) has an above-average late-delivery rate (11.3%), unlike SP (the #1 revenue state), which performs well operationally (4.3% late)
- **The issue isn't just regional** — the platform's top revenue-generating seller also has an above-average late rate (10.5%)

## 💡 Recommendations
- Prioritize logistics investment in RJ, a top-3 revenue state with nearly double the platform's average late rate
- Audit high-revenue sellers with above-average late rates, starting with the top seller identified above
- Treat delivery speed as a satisfaction lever — the ~2-point review score drop tied to late orders links logistics directly to retention
- Use the $2.25M revenue-at-risk figure to justify investment in delivery reliability

## 📁 Dataset
[Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) 
(via Kaggle)

![Revenue at Risk](Images/Revenue%20At%20Risk.png)

![Top 10 States by Late Deliveries](Images/Top%2010%20States%20By%20Late%20Deliveries.png)

## 📂 Structure
```


├── Notebook/    → analysis notebook
├── Images/      → exported charts
└── Olist/       → raw dataset
```
