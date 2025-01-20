# Credit Card Fraud Detection - Exploratory Data Analysis (EDA) 💳🔍

## Overview
This project focuses on **Exploratory Data Analysis (EDA)** of a credit card fraud detection dataset. The dataset contains **284,807 transactions** and 31 features, where the target variable (`Class`) indicates whether a transaction is **legitimate (0)** or **fraudulent (1)**. The goal of this analysis is to understand the data, uncover insights, and prepare for machine learning models.

---

## Key Steps
### 1. **Data Understanding**
- Dataset: `credit card.csv` with 31 columns including:
  - **Features**: `Time`, `V1-V28` (anonymized), `Amount`.
  - **Target**: `Class` (0 = Legitimate, 1 = Fraudulent).
- Total rows: 284,807  
- Class Imbalance: Fraudulent transactions account for only **0.17%**.

### 2. **EDA Steps**
- **Data Cleaning**: Checked and confirmed no missing or null values.
- **Statistical Analysis**: Summarized key statistics like mean, median, and standard deviation for numerical features.
- **Visualizations**:
  - **Countplot**: Distribution of fraudulent vs legitimate transactions.
  - **Histogram**: Distribution of transaction amounts.
  - **Heatmap**: Correlation between numerical features.

### 3. **Key Findings**
- Significant **class imbalance**: Fraudulent transactions are very rare.
- **Transaction Amount Distribution**: Highly skewed with a few large outliers.
- **Correlation Insights**: Weak correlations between features and the target variable.

---

## Tools & Libraries
- **Python**: Programming language.
- **Pandas**: For data manipulation.
- **Matplotlib** & **Seaborn**: For creating visualizations.
- **Jupyter Notebook**: For interactive analysis.

---

## Visualizations
### Countplot
Comparison of legitimate vs fraudulent transactions.  
Example code:
```python
import seaborn as sns
sns.countplot(x='Class', data=df, palette=['blue', 'red'])
```

### Correlation Heatmap
Visualizing relationships between features:
```python
sns.heatmap(df.corr(), annot=True, cmap='coolwarm', fmt='.2f', linewidths=0.5)
```

---

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/ArsalAli786/credit-card-fraud-eda.git
   ```
2. Navigate to the project directory:
   ```bash
   cd credit-card-fraud-eda
   ```
3. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn
   ```
4. Run the Jupyter Notebook to see the analysis:
   ```bash
   jupyter notebook
   ```

---

## Acknowledgements
- Dataset: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- Tools: Python, Pandas, Matplotlib, Seaborn.

---

Feel free to contribute or raise issues! 🚀
