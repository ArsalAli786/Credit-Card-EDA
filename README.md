# 🩺 Heart Disease Data Analysis  

## Overview  
This project involves analyzing a heart disease dataset to uncover patterns, trends, and insights into factors contributing to heart disease. The analysis explores key health metrics such as cholesterol levels, resting blood pressure, chest pain types, and exercise-induced angina, comparing patients with and without heart disease while also assessing its severity.

---

## Dataset  
**Source**: [Heart Disease Dataset](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data)  

The dataset includes the following columns:  
- **id**: Unique ID for each patient  
- **age**: Age of the patient in years  
- **origin**: Place of study  
- **sex**: Gender (Male/Female)  
- **cp**: Chest pain type (typical angina, atypical angina, non-anginal pain, asymptomatic)  
- **trestbps**: Resting blood pressure (in mm Hg)  
- **chol**: Serum cholesterol in mg/dl  
- **fbs**: Fasting blood sugar > 120 mg/dl (True/False)  
- **restecg**: Resting electrocardiographic results (normal, ST-T abnormality, left ventricular hypertrophy)  
- **thalach**: Maximum heart rate achieved  
- **exang**: Exercise-induced angina (True/False)  
- **oldpeak**: ST depression induced by exercise relative to rest  
- **slope**: Slope of the peak exercise ST segment  
- **ca**: Number of major vessels (0-3) colored by fluoroscopy  
- **thal**: Thalassemia (normal, fixed defect, reversible defect)  
- **num**: Target variable (0 = no heart disease, 1-4 = presence/severity of heart disease)  

---

## What I Did  
1. **Data Exploration**:  
   - Analyzed the target variable (`num`) for the presence and severity of heart disease.  
   - Checked for outliers in `chol` (cholesterol) and `trestbps` (resting blood pressure).  

2. **Cholesterol Comparison**:  
   - Compared average cholesterol levels between patients with and without heart disease.  
   - Used boxplots and Interquartile Range (IQR) to detect and visualize outliers.  

3. **Distribution Analysis**:  
   - Visualized age and gender distribution of patients.  
   - Analyzed chest pain types to identify the most common ones.  

---

## Tools & Libraries  
- **Python**: Core programming language for analysis  
- **Pandas**: For data manipulation and exploration  
- **Matplotlib & Seaborn**: For data visualization (e.g., boxplots, histograms)  
- **Jupyter Notebook**: Interactive environment for data analysis  

---

## Key Findings  
- Patients with heart disease exhibited unexpectedly lower average cholesterol levels, potentially due to medication or other influencing factors.  
- Outliers were present in cholesterol and resting blood pressure, emphasizing the need for further investigation or cleaning.  
- The age and gender distributions revealed interesting demographic trends in the dataset.  

---

## Visualizations  
Key plots generated during the analysis include:  
- **Boxplots**: Highlighted outliers in cholesterol and resting blood pressure.  
- **Histograms**: Showed age distribution among patients.  
- **Bar Charts**: Summarized chest pain type counts.  

---

## How to Use  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/heart-disease-analysis.git
   ```  
2. Install the required Python libraries:  
   ```bash
   pip install pandas matplotlib seaborn
   ```  
3. Open the Jupyter Notebook and run the analysis:  
   ```bash
   jupyter notebook heart_disease_analysis.ipynb
   ```  

---

## Future Work  
- Perform feature engineering to improve the quality of insights.  
- Apply machine learning models to predict heart disease severity.  
- Investigate other risk factors beyond cholesterol and resting blood pressure.  

---

## License  
This project is licensed under the [MIT License](LICENSE).  

---

## Acknowledgments  
Special thanks to [Kaggle](https://www.kaggle.com) for providing the dataset.  

---

Feel free to explore, contribute, or reach out with questions!  
#DataScience #HeartDisease #PythonAnalysis #OpenSource  
```  

Let me know if you want to customize further! 🚀
