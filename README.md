# Internship_Project-IBM_HR_Analytics_Employee_Attrition-And-Performance

A data analytics and machine learning project to **identify critical factors behind employee attrition** and **predict employees at risk of leaving**, using HR data provided by IBM.

---

## Project Summary

This project analyzes a fictional IBM HR dataset to understand **why employees leave the company** and provide **data-driven insights to improve employee retention**.

### Key Steps:
- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Attrition Factor Analysis  
- Predictive Modeling using Random Forest  
- Insights & Business Recommendations  

---

## Technologies Used

| Tool / Library | Purpose |
|----------------|---------|
| **Python** | Data analysis & modeling |
| **Pandas, NumPy** | Data manipulation |
| **Seaborn, Matplotlib** | Visualization |
| **Scikit-learn** | Machine Learning |

---

## Dataset Information

- **Total Records:** 1,470  
- **Features:** 35  
- **No Missing or Duplicate Values**  
- **Target Variable:** `Attrition` (Yes/No)

Dataset includes:
- Demographics (Age, Gender, Marital Status)  
- Job Details (Role, Department, Business Travel)  
- Salary & Income  
- Experience (YearsAtCompany, TotalWorkingYears)  
- Performance & Satisfaction Indicators  

---

## Key Insights

| Factor | Observation |
|--------|-------------|
| **Attrition Rate** | 16.12% employees left |
| **Age Group** | 25–35 years have highest attrition |
| **Salary** | Lower income employees more likely to leave |
| **Distance from Home** | Higher commute distance = more attrition |
| **Business Travel** | Frequent travelers show 25% more attrition |
| **Experience** | Employees with 0–5 years most likely to switch |
| **Gender** | 63.29% of attrition cases were male |

---

## Machine Learning Model

| Model | Algorithm | Evaluation |
|-------|-----------|------------|
| Employee Attrition Prediction | Random Forest Classifier | Accuracy Score, Confusion Matrix, Classification Report |

### ML Workflow
1. Label encoding categorical variables  
2. Train-test split  
3. Model training using Random Forest  
4. Performance evaluation  

---

## Recommendations

✔ Provide better salary growth  
✔ Reduce excessive business travel  
✔ Implement hybrid/work-from-home flexibility  
✔ Create strong career growth programs for younger employees  
✔ HR team to actively focus on employee engagement initiatives  

---

##  How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Veer7733/Internship_Project-IBM_HR_Analytics_Employee_Attrition-And-Performance
   ``` 
2. Navigate to the project folder:
   ```bash
   cd Internship_Project-IBM_HR_Analytics_Employee_Attrition-And-Performance
   ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook IBM HR Analytics Employee Attrition & Performance.ipynb
   ```
