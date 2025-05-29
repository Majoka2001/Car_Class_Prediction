# 🚗 Car Evaluation: Categorical Feature Association Analysis

This project explores the relationships between categorical features in the **Car Evaluation Dataset** using statistical association tests like chi2 test, spearman correlation coefficient and kendall tau before proceeding to preprocessing tasks like feature encoding, feature engineering and scaling and handling data imbalance using SMOTE. Then, an SVC classifier is used to make predictions about Car Classes on test data. 

---

## 📊 Objective

Before diving into machine learning, it's crucial to know which features are potentially **informative** and **correlated**—both with each other and with the target variable. This notebook answers questions like:

- Are `maintenance cost` and `safety` levels related?
- Do cars with higher buying cost usually have high maintenance cost as well?
- How does seating capacity of a car correlate to its number of doors?
- Which features show **statistical dependence** on the **target class**?

---

## 🧪 Techniques Used

- **Chi-Square Test of Independence**  
  To statistically evaluate if two categorical variables are related.

- **Cramér’s V**  
  To quantify the **strength** of association between categorical variables (scale: 0 to 1).

- **Spearman's Correlation Coefficient and Kendall Tau**
  To assess how strongly the categorical features correlate to each other and the direction of correlation.  

- **Heatmaps**  
  For visual representation of contingency tables.

- **StandardScaler**
  For scaling the features in the dataset before proceeding to machine learning.

- **SMOTE**
  To handle the imbalance in the training set so majority classes do not dominate the minority classes when it comes to class prediction. 

---

## 📁 Dataset

The project uses the dataset at: [(https://archive.ics.uci.edu/dataset/19/car+evaluation)], which includes features like:

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

