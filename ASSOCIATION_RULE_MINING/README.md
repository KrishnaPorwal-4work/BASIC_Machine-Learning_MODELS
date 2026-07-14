# 🛒 Association Rule Mining using Apriori & FP-Growth

A complete implementation of **Association Rule Mining (Market Basket Analysis)** using the **Apriori** and **FP-Growth** algorithms in Python.

This project discovers hidden purchasing patterns from supermarket transaction data and generates meaningful association rules that can be used for recommendation systems, cross-selling, and business decision-making.

---

## 📌 Project Overview

Association Rule Mining is an unsupervised machine learning technique used to identify relationships between items frequently purchased together.

In this project:

- Performed transaction-based data preprocessing
- Implemented the Apriori algorithm
- Implemented the FP-Growth algorithm
- Generated and analyzed association rules
- Compared both algorithms
- Visualized important metrics such as Support, Confidence, and Lift
- Derived business insights from discovered patterns

---

## 📂 Dataset

The dataset contains supermarket transaction records.

- Each row represents **one customer transaction**
- Each column represents **an item purchased**
- Empty (`NaN`) values indicate that the corresponding item was **not purchased**

The dataset is suitable for Market Basket Analysis because every transaction contains a collection of purchased products.

---

## 🚀 Algorithms Used

### 1. Apriori Algorithm

Apriori discovers frequent itemsets by generating candidate item combinations and filtering them using minimum support.

### 2. FP-Growth Algorithm

FP-Growth builds an FP-Tree to efficiently mine frequent patterns without generating candidate itemsets, making it more suitable for larger datasets.

---

## 📊 Evaluation Metrics

The association rules are evaluated using:

- **Support**
- **Confidence**
- **Lift**

These metrics help identify strong and meaningful relationships between products.

---

## 📈 Visualizations

The notebook includes:

- Top Purchased Items
- Basket Size Distribution
- Top Association Rules by Lift
- Support Distribution
- Confidence Distribution
- Support vs Confidence Scatter Plot
- Apriori vs FP-Growth Comparison

---

## 💼 Business Applications

Association Rule Mining can be applied to:

- 🛍️ Market Basket Analysis
- 🎯 Product Recommendation Systems
- 📦 Product Bundling
- 💰 Cross-selling & Upselling
- 🏪 Store Layout Optimization
- 📊 Customer Purchase Behavior Analysis

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Apyori
- Mlxtend

---

## 📁 Project Structure

```
Association-Rule-Mining/
│
├── Association_Mining.ipynb
├── Market_Basket_Optimisation.csv
├── README.md
└── requirements.txt
```

---

## 📌 Key Learnings

- Transaction Data Preprocessing
- Market Basket Analysis
- Association Rule Mining
- Apriori Algorithm
- FP-Growth Algorithm
- Support, Confidence & Lift
- Data Visualization
- Business Insight Generation

---

## 🔮 Future Improvements

Possible enhancements include:

- Building a Product Recommendation System
- Deploying the project using Streamlit
- Testing on larger retail datasets
- Comparing additional frequent pattern mining algorithms
- Interactive dashboard for business users

---

## 📷 Sample Output

The notebook generates:

- Frequent Itemsets
- Association Rules
- Lift-based Rule Ranking
- Business Insights
- Comparison between Apriori and FP-Growth

---

## 🤝 Contributing

Contributions, suggestions, and improvements are always welcome.

---

## 📜 License

This project is intended for educational and learning purposes.