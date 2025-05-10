# 🚢 Titanic Data Analysis & Visualization

This project explores the **Titanic dataset** using **Seaborn**, **Matplotlib**, and **Pandas**. It showcases exploratory data analysis (EDA), helping uncover key insights about passenger survival on the Titanic.

---

## 📊 Project Overview

- **Objective:** Analyze and visualize survival patterns using demographic and ticketing data.
- **Dataset:** Seaborn's built-in Titanic dataset.
- **Skills Demonstrated:**
  - Data exploration & cleaning
  - Visual storytelling with Seaborn & Matplotlib
  - Multivariate analysis
  - Clustering analysis

---

## 🛠️ Tools & Libraries

- Python 3.x
- Pandas
- Seaborn
- Matplotlib
- NumPy
- Scikit-learn (for clustering)

---

## 📂 Dataset Features

Key features include:

- `survived` (0 = No, 1 = Yes)
- `pclass` (Ticket class)
- `sex`
- `age`
- `fare`
- `embarked` (Port of embarkation)
- `sibsp`, `parch` (Family info)
- `deck`, `embark_town`

---

## 📈 Charts & Insights

### 1️⃣ Missing Values Heatmap

- **Chart:** Heatmap showing where missing values exist in the dataset.
- **Insight:**
  - Significant missing data in `age`, `deck`, and `embarked`.
  - Highlights the importance of **data cleaning and imputation** before deeper analysis.
    <img width="354" alt="image" src="https://github.com/user-attachments/assets/3bb3b8a8-9ab3-46f2-969d-fb21af914847" />

---

### 2️⃣ Survival Rate by Class & Gender (Barplot)

- **Chart:** Barplot of survival rate across classes (1st, 2nd, 3rd), split by gender.
- **Insight:**
  - **Females had a much higher survival rate** than males across all classes.
  - **1st class passengers** were more likely to survive than 2nd and 3rd class.
  - Demonstrates the **influence of both gender and socioeconomic status.**
    <img width="365" alt="image" src="https://github.com/user-attachments/assets/3d301c79-3d00-466c-bb22-7e540bba8fdb" />


---

### 3️⃣ Age Distribution by Survival (Violin Plot)

- **Chart:** Violin plot of passenger ages, showing distributions for survivors vs. non-survivors, split by gender.
- **Insight:**
  - **Young children (under 10)** had a noticeably higher survival rate.
  - Non-survivors covered a broader age range, especially among males.
  - This confirms **age and gender as strong survival factors.**
    <img width="360" alt="image" src="https://github.com/user-attachments/assets/cefbdc5f-3c0c-415c-8ae2-85c21c33619d" />


---

### 4️⃣ Pairplot of Age, Fare, Pclass & Survival

- **Chart:** Pairplot visualizing the relationships between `age`, `fare`, `pclass`, and `survival`.
- **Insight:**
  - A strong **correlation between fare and class** (higher class = higher fare).
  - Survivors were **clustered in higher classes with higher fares.**
  - Multivariate patterns emerge, confirming multiple factors affected survival.
    <img width="428" alt="image" src="https://github.com/user-attachments/assets/fd8c6258-c01c-4055-8006-3c5a8d4382a2" />


---

### 5️⃣ Mean Survival Rate by Family Size & Gender (Barplot)

- **Chart:** Barplot showing mean survival rate by family size, split by gender.
- **Insight:**
  - **Medium-sized families (2–4 members)** had better survival rates.
  - Very large or solo passengers had lower survival odds.
  - Gender gap is visible: **females consistently had higher survival rates.**
    <img width="301" alt="image" src="https://github.com/user-attachments/assets/ec559e05-0a2e-4c93-ab0f-50c27ff385e8" />

---

### 6️⃣ Correlation Matrix (Heatmap)

- **Chart:** Heatmap showing correlation coefficients between numerical features.
- **Insight:**
  - Positive correlation between **fare and survival**.
  - **Pclass and survival** are inversely correlated.
  - Family size has minimal direct correlation but combined with other factors, may still matter.
    <img width="312" alt="image" src="https://github.com/user-attachments/assets/9a517cdd-f0b2-4b26-8668-b2a47a94fb2a" />


---

### 7️⃣ Fare Distribution by Embarkation & Survival (Box Plot)

- **Chart:** Box plot of fares paid by embarkation port (`embarked`), split by survival.
- **Insight:**
  - Passengers embarking from **Cherbourg (C)** paid higher fares and had a higher survival rate.
  - Fare variability was **largest in Cherbourg**, indicating wealth disparity within embarkation points.
    <img width="300" alt="image" src="https://github.com/user-attachments/assets/fb6b8d84-ec5c-4592-bcb5-dbf02704f123" />


---

### 8️⃣ Clusters Based on Age & Fare (Scatter Plot)

- **Chart:** Scatter plot with **KMeans clustering** applied to `age` and `fare`.
- **Insight:**
  - Three distinct clusters emerge based on age and fare.
  - Clusters reflect different **passenger groups (e.g., young/low fare, older/high fare)**.
  - Adds an **unsupervised learning dimension**, showing natural groupings in the data.
    <img width="301" alt="image" src="https://github.com/user-attachments/assets/c9641f16-5975-47df-8860-f152e397839f" />



---

## 🎯 Key Visual Insights Summary

🟢 **Women** had much higher survival rates across all classes.

🔵 **First-class passengers** had the highest survival probability (over 60%).

🟠 **Small families** (2–4 members) showed better survival than solo travelers or large families.

🟡 **Fare and age** have clusters that roughly separate survival likelihoods.

🔴 The **embarkation point** appears linked to ticket fare distributions.

---


