# Predicting Employee Stress Levels Using Machine Learning

This project aims to analyze employee work-life related features and predict stress levels using supervised Machine Learning techniques. The project was built as part of the Microsoft AINSI Internship and is aligned with real-world applications of AI and data analytics in workplace well-being.

---

## 🔍 Problem Statement

Employee stress is a growing concern in today's work environments. Identifying stress levels early using data-driven methods can help organizations support employee wellness and improve retention.

---

## 🎯 Objectives

- Explore and analyze work-life related features such as work pressure, job satisfaction, and manager support.
- Develop a Machine Learning model to predict employee stress levels.
- Identify key features contributing to stress and visualize their impact.
- Demonstrate how ML can support organizational decision-making in employee well-being.

---

## 📂 Dataset

- **Source**: Provided for academic internship use.
- **Format**: CSV file (`train.csv`)
- **Features**:
  - `Avg_Working_Hours_Per_Day`
  - `Work_From`, `Work_Pressure`, `Manager_Support`, `Sleeping_Habit`, etc.
  - Target Variable: `Stress_Level` (1 to 5)

---

## 🛠️ Tools & Technologies

- Python
- Google Colab / Jupyter Notebook
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`

---

## 📊 Methodology

1. **Data Cleaning & Preprocessing**
   - Handled missing values and categorical encoding.
2. **Exploratory Data Analysis (EDA)**
   - Visualized feature distributions and correlations.
3. **Model Building**
   - Applied and evaluated Random Forest Classifier.
4. **Model Evaluation**
   - Accuracy, Confusion Matrix, and Classification Report used.
5. **Improvement**
   - Tuned Random Forest using hyperparameters.
6. **Feature Importance**
   - Analyzed which features contribute most to predicting stress.

---

## 📉 Results

- Initial Random Forest Accuracy: **20.83%**
- Tuned Random Forest Accuracy: **19.67%**
- Accuracy remained low, likely due to limited feature diversity and complexity of stress prediction.

---

## 📌 Key Insights

- Work pressure, manager support, and job satisfaction were among the more impactful features.
- Human stress depends on various personal and external factors not captured in this dataset.
- Grouping stress levels or collecting more detailed features may improve model performance.

---

## 🚀 Future Improvements

- Collect larger and more diverse datasets.
- Engineer new features such as combined scores or stress trends.
- Use regression or classification with grouped stress levels (low/medium/high).

---

## 📁 Project Status

✅ Completed basic ML pipeline and analysis  
🚧 Further improvements possible with richer datasets and advanced techniques

---

## 📎 Author

**Swati Hegde**  
MSc in Statistics | Data Analyst Intern  
Part of Microsoft AINSI Internship – Edunet Foundation

---

## 📌 Disclaimer

This project is for academic and learning purposes. The dataset is limited in scope and may not represent real-world employee behavior comprehensively.
