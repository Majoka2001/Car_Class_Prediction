# 🚗 Car Evaluation: Categorical Feature Association Analysis

This project explores the relationships between categorical features in the **Car Evaluation Dataset** using statistical association tests. The aim is to deeply understand the structure of the data before proceeding to feature encoding and machine learning.

---

## 📊 Objective

Before diving into machine learning, it's crucial to know which features are potentially **informative** and **correlated**—both with each other and with the target variable. This notebook answers questions like:

- Are `maintenance cost` and `safety` levels related?
- Do `number of doors` and `passenger capacity` influence each other?
- Which features show **statistical dependence** on the **target class**?

---

## 🧪 Techniques Used

- **Chi-Square Test of Independence**  
  To statistically evaluate if two categorical variables are related.

- **Cramér’s V**  
  To quantify the **strength** of association between categorical variables (scale: 0 to 1).

- **Heatmaps**  
  For visual representation of contingency tables.

- **Spearman's Rank Correlation**  
  (Optional) For testing ordinal relationships when applicable.

---

## 📁 Dataset

The project uses the [UCI Car Evaluation Dataset](https://archive.ics.uci.edu/ml/datasets/car+evaluation), which includes features like:

- `buying`: buying price
- `maint`: maintenance cost
- `doors`: number of doors
- `persons`: capacity in terms of persons to carry
- `lug_boot`: size of luggage boot
- `safety`: safety level
- `class`: the overall car evaluation (target)

---

## 🔍 Key Insights

- Some features, like `maint` and `safety`, were shown to be **statistically independent** in this dataset due to perfectly balanced categorical distributions.
- Features like `doors` vs `persons` were investigated to uncover practical correlations.
- Visual and quantitative analyses were combined to ensure a robust understanding of feature relationships.

---

## 🛠️ Future Work

- Perform similar association checks between **each feature and the target**.
- Choose encoding strategies based on whether features are **ordinal or nominal**.
- Proceed to machine learning modeling (e.g., Decision Trees, Random Forests).
- Evaluate model performance and interpret feature importance.

---

## 📌 Requirements

- Python 3.7+
- pandas
- scipy
- seaborn
- matplotlib
- scikit-learn (for encoding and ML, if proceeding)

---

## 🧠 Author Notes

This project is meant to showcase not just data modeling, but the **thoughtful, analytical groundwork** that precedes it. It demonstrates how **statistical insight** can guide better modeling decisions.

---

