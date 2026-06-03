# Titanic Data Analysis with EDA

## Introduction

This project performs an exploratory data analysis (EDA) on the Titanic dataset using Python.

The notebook demonstrates data cleaning, handling missing values, feature engineering, statistical analysis, and visualization techniques to identify patterns and factors that influenced passenger survival.

The analysis includes answering analytical questions and creating visualizations using Matplotlib and Seaborn.

---

## Project Structure

```bash
.
├── Task_3_Titanic_Data_Analysis_With_EDA.ipynb   # Main Jupyter Notebook
├── titanic_dataset.csv                           # Titanic dataset
└── README.md                                     # Project documentation
```

---

## Dataset Information

The dataset contains information about Titanic passengers, including:

* Passenger ID
* Survival status
* Passenger class
* Name
* Gender
* Age
* Number of siblings/spouses aboard
* Number of parents/children aboard
* Ticket number
* Fare
* Cabin
* Port of embarkation

---

## Dataset Shape

The Titanic dataset used in this project contains:

* **Rows:** 419
* **Columns:** 12

This dataset provides demographic and travel-related information for passengers aboard the Titanic, which is used to analyze survival patterns and trends.

---

## Objectives

The main objectives of this project are:

1. Clean and preprocess the Titanic dataset
2. Handle missing values in important columns
3. Create new features for analysis
4. Perform exploratory data analysis
5. Analyze:

   * Survival rate by age group
   * Survival rate by embarkation port
   * Survival rate by family size
6. Create meaningful visualizations
7. Identify patterns affecting passenger survival

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

---

## Installation

1. Clone the repository or download the files.

2. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn notebook
```

3. Launch Jupyter Notebook:

```bash
google colab
```

4. Open:

```bash
Task_3_Titanic_Data_Analysis_With_EDA.ipynb
```

---

## Data Cleaning

The notebook includes preprocessing steps such as:

* Handling missing values
* Filling missing age values using the mean
* Removing unnecessary columns
* Checking data types
* Preparing data for analysis and visualization

---

## Feature Engineering

A new feature is created:

```python
FamilySize = SibSp + Parch
```

This feature helps analyze the relationship between family size and passenger survival.

---

## Visualizations

The project includes visualizations such as:

* Age distribution histogram
* Correlation heatmap
* Survival rate by family size bar chart
* Comparative survival analysis plots

---

## Key Learning Outcomes

Through this project, you can learn:

* Data cleaning techniques
* Missing value handling
* Feature engineering
* Exploratory data analysis (EDA)
* Statistical observations from datasets
* Data visualization using Matplotlib and Seaborn
* Data-driven decision making

---

## How to Run

1. Ensure the dataset file is in the same directory as the notebook.
2. Run all notebook cells sequentially.
3. Review generated charts, summaries, and analytical outputs.

---

## Future Improvements

Possible enhancements include:

* Machine Learning survival prediction models
* Advanced feature engineering
* Statistical hypothesis testing
* Interactive dashboards using Plotly or Streamlit
* Model performance comparison

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Author

**Jenil M. Panchal**   
(Data Science Enthusiast)
