# Loan Risk Prediction & Client Data Analysis

## 📌 Overview
This project analyzes client financial and demographic data to assess loan default risk.
Using data visualization and machine learning techniques, we explore key factors that
influence credit risk and build a predictive model using a Random Forest classifier.

The project combines:
- Exploratory Data Analysis (EDA)
- Data visualization using Python
- Machine learning-based risk classification

---

## 🧑‍💻 Author
**Name:** Heshika Pokala  
**Email:** heshikapokala@gmail.com  

---

## 📊 Data Visualization
After loading the dataset (JSON format), multiple visualizations are created using
**Matplotlib** and **Seaborn** to understand data distribution and client behavior.

### Visualizations Included:
- **Income Distribution**  
  Shows income range and frequency, helping assess financial stability.

- **Age Distribution**  
  Identifies age demographics and risk patterns across age groups.

- **Experience Distribution**  
  Displays professional experience levels, indicating earning potential and stability.

- **Current Job Years Distribution**  
  Highlights job tenure, an important factor in default risk assessment.

- **Current House Years Distribution**  
  Indicates residential stability among clients.

- **Marital Status Count**  
  Compares married vs single clients and their financial behavior trends.

- **Risk Flag Count**  
  Shows the proportion of high-risk and low-risk clients.

- **Age vs Risk Flag**  
  Box plot comparing age distribution across risk categories.

- **Income vs Risk Flag**  
  Box plot showing income differences between high-risk and low-risk clients.

---

## 🔍 Data Exploration Insights
- **Income:** Right-skewed distribution with most clients earning lower incomes.
- **Age:** Fairly uniform distribution with peaks in certain age ranges.
- **Experience:** Higher frequency of clients with fewer years of experience.
- **Current Job Years:** Most clients have shorter job tenures.
- **Current House Years:** Fairly uniform with slight right skew.
- **Marital Status:** Single clients outnumber married clients.
- **House Ownership:** Majority of clients live in rented houses.
- **Car Ownership:** Many clients do not own a car.
- **Profession:** Multiple professions represented with varying frequencies.

---

## 🤖 Model Selection

### Why Random Forest?
Random Forest is chosen due to its:
- High accuracy and robustness
- Ability to reduce overfitting through ensemble learning
- Capability to model complex non-linear relationships
- Feature importance analysis for interpretability
- Flexibility in handling different data types and missing values

---

## 📈 Model Performance

| Metric     | Score  |
|------------|--------|
| Accuracy   | 0.8992 |
| Precision  | 0.6072 |
| Recall     | 0.5314 |
| F1 Score   | 0.5668 |

---

## 🧠 Key Factors Influencing Risk
Based on feature importance analysis, the main factors affecting loan risk are:
- **Income**
- **Age**
- **Professional Experience**
- **Current Job Years**
- **Current House Years**

These insights help lenders understand client behavior and improve risk assessment strategies.

---

## 🛠️ Technologies Used
- Python
- Matplotlib
- Seaborn
- Scikit-learn
- Pandas
- NumPy

---

## 📌 Conclusion
This project demonstrates how combining data visualization with machine learning can
provide actionable insights for loan risk assessment. The Random Forest model delivers
strong predictive performance while maintaining interpretability, making it suitable
for real-world financial decision-making.
