# 🚢 Titanic Survival Analysis – End-to-End EDA

### 📌 Project Objective
To perform a **comprehensive exploratory data analysis (EDA)** on the Titanic dataset to uncover the key factors that influenced passenger survival.

---

## 🧠 Theoretical Concept: What is EDA?
Exploratory Data Analysis (EDA) is the process of investigating datasets to discover patterns, spot anomalies, test hypotheses, and check assumptions using summary statistics and visualizations.  
It helps in:
- Understanding data distributions and relationships  
- Handling missing values and outliers  
- Guiding feature engineering and model selection  

---

## 🧩 Steps Performed
1. **Setup & Imports** – Loaded Pandas, NumPy, Seaborn, Matplotlib  
2. **Data Loading** – Imported Titanic dataset from GeeksforGeeks repo  
3. **Data Cleaning** – Handled missing values, created “Has_Cabin” feature  
4. **Univariate Analysis** – Distribution of each variable  
5. **Bivariate Analysis** – Relationship with target (`Survived`)  
6. **Feature Engineering** – Created `FamilySize`, `IsAlone`, `Title` features  
7. **Multivariate Analysis** – Combined feature effects  
8. **Correlation Analysis** – Found strongest relationships with survival  

---

## 📊 Key Insights
- **Sex** is the strongest predictor of survival — females survived far more often.  
- **Pclass** shows a clear survival gradient (1st class > 2nd > 3rd).  
- **Fare** correlates positively with survival (wealthier passengers had higher survival).  
- **IsAlone** passengers had much lower survival rates.  
- **Titles** extracted from names revealed social-status-based differences.

---

## 🧾 Libraries Used

pandas
numpy
matplotlib
seaborn
---

## 🔗 Google Collab Link

https://colab.research.google.com/drive/1EOtrfP0V-s2XPJOz40bWsBkQzIzJen4O?authuser=1#scrollTo=ASxUkGhWyE9D

---

## 📈 Visualizations
Includes:
- Count plots for categorical variables  
- Histograms for Age and Fare  
- Boxplot for Fare outliers  
- Bar plots for relationships with survival  
- Correlation heatmap

---

## 💡 Conclusion
EDA revealed that **gender, class, fare, and family structure** were the most significant factors in determining survival.  
This analysis builds a strong foundation for further **predictive modelling**.

---