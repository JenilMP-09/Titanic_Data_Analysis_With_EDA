# 🚢 Titanic Data Analysis with Exploratory Data Analysis (EDA)

<div align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)
![License](https://img.shields.io/badge/License-Educational-lightgrey)

A mini Exploratory Data Analysis (EDA) project on the Titanic dataset, focusing on data cleaning, feature engineering, statistical analysis, and visualization of passenger survival patterns.

</div>

---

## 📌 Project Overview

This project explores the famous Titanic dataset to identify factors that influenced passenger survival. The analysis includes:

- Data cleaning and preprocessing
- Missing value handling
- Feature engineering
- Survival analysis across different demographics
- Exploratory visualizations
- Correlation analysis

The notebook was created as part of a Data Science learning exercise to strengthen practical EDA skills using Python.

---

## 📂 Project Structure

```text
.
├── Task_3_Titanic_Data_Analysis_With_EDA.ipynb
├── titanic_dataset.csv
└── README.md
```

---

## 🎯 Objectives

### Data Cleaning
- Fill missing values in the `Age` column using the mean.
- Remove less useful columns such as `Cabin`.
- Prepare the dataset for analysis.

### Exploratory Analysis
- Survival rate by age group.
- Survival rate by embarkation port.
- Survival rate by family size.
- Statistical summaries of numerical features.

### Visualization
- Age distribution histogram.
- Correlation heatmap.
- Survival rate by family size bar chart.

---

## 🛠️ Technologies Used

| Tool | Purpose |
|--------|---------|
| Python | Programming Language |
| Pandas | Data Manipulation |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Jupyter Notebook | Interactive Analysis |

---

## ⚙️ Installation

Clone the repository:

```bash
git clone <your-repository-url>
cd <repository-name>
```

Install dependencies:

```bash
pip install pandas matplotlib seaborn notebook
```

---

## ▶️ Usage

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Task_3_Titanic_Data_Analysis_With_EDA.ipynb
```

Run all cells sequentially to reproduce the analysis.

---

## 📊 Dataset

The Titanic dataset contains information about passengers aboard the RMS Titanic, including:

- Passenger Class (`Pclass`)
- Sex
- Age
- Fare
- Embarkation Port (`Embarked`)
- Family Information (`SibSp`, `Parch`)
- Survival Status (`Survived`)

Target variable:

```text
Survived
0 = Did Not Survive
1 = Survived
```

---

## 🔍 Feature Engineering

A new feature is created:

```python
FamilySize = SibSp + Parch
```

This helps analyze the relationship between family size and survival probability.

---

## 📈 Sample Visualizations

### Age Distribution

Add your screenshot:

```text
screenshots/age_distribution.png
```

![Age Distribution](screenshots/age_distribution.png)

---

### Correlation Heatmap

Add your screenshot:

```text
screenshots/correlation_heatmap.png
```

![Correlation Heatmap](screenshots/correlation_heatmap.png)

---

### Survival Rate by Family Size

Add your screenshot:

```text
screenshots/family_size_survival.png
```

![Family Size Survival](screenshots/family_size_survival.png)

---

## 📋 Key Findings

- Missing values in passenger age were successfully handled.
- Family size appears to influence survival rates.
- Passenger demographics show varying survival outcomes.
- Correlation analysis helps identify relationships among numerical variables.

---

## 🚀 Future Enhancements

- Build machine learning models for survival prediction.
- Add feature importance analysis.
- Perform advanced statistical testing.
- Create interactive dashboards using Plotly or Streamlit.
- Compare multiple classification algorithms.

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Submit a pull request.

---

## 📝 License

This project is intended for educational and learning purposes.

---

## 👨‍💻 Author

Developed as part of a Data Science and Exploratory Data Analysis learning project.

⭐ If you found this project useful, consider giving the repository a star.
