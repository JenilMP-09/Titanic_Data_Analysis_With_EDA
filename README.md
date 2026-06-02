# Titanic Data Analysis with Exploratory Data Analysis (EDA)

## Project Overview
This project performs a mini Exploratory Data Analysis (EDA) on the Titanic dataset. The notebook demonstrates data cleaning, handling missing values, feature engineering, statistical analysis, and data visualization to uncover patterns related to passenger survival.

## Project Files

- `Task_3_Titanic_Data_Analysis_With_EDA.ipynb` — Jupyter Notebook containing the complete analysis workflow.
- `titanic_dataset.csv` — Titanic dataset used for analysis.
- `README.md` — Project documentation.

## Objectives

### Data Cleaning
- Fill missing values in the `Age` column using the mean age.
- Remove less useful columns such as `Cabin`.
- Prepare the dataset for analysis and visualization.

### Analysis Tasks
- Survival rate by age group.
- Survival rate by embarkation port (`Embarked`).
- Survival rate by family size (`SibSp + Parch`).

### Visualizations
- Age distribution histogram.
- Correlation heatmap.
- Survival rate by family size bar chart.

## Dataset Information

The dataset contains passenger information such as:

- Passenger ID
- Passenger Class (`Pclass`)
- Name
- Sex
- Age
- Number of siblings/spouses aboard (`SibSp`)
- Number of parents/children aboard (`Parch`)
- Ticket information
- Fare
- Cabin
- Embarkation port (`Embarked`)
- Survival status (`Survived`)

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Installation

1. Clone or download the project files.
2. Install required dependencies:

```bash
pip install pandas matplotlib seaborn notebook
```

## Usage

1. Launch Jupyter Notebook:

```bash
jupyter notebook
```

2. Open:

```text
Task_3_Titanic_Data_Analysis_With_EDA.ipynb
```

3. Run all notebook cells sequentially.

## Feature Engineering

The notebook creates a new feature:

```python
FamilySize = SibSp + Parch
```

This feature is used to analyze how family size affects survival rates.

## Visual Outputs

### 1. Age Distribution
Histogram displaying passenger age distribution.

### 2. Correlation Heatmap
Heatmap showing relationships among numerical variables.

### 3. Survival Rate by Family Size
Bar chart illustrating survival trends across family sizes.

## Key Learning Outcomes

- Data cleaning and preprocessing
- Missing value imputation
- GroupBy analysis with Pandas
- Feature engineering
- Statistical summaries
- Data visualization using Seaborn and Matplotlib
- Exploratory Data Analysis (EDA) workflow

## Troubleshooting

### Missing Libraries

If you encounter import errors:

```bash
pip install pandas matplotlib seaborn
```

### Dataset Not Found

Ensure `titanic_dataset.csv` is located in the expected path or update the file path in the notebook.

## Future Improvements

- Additional survival prediction analysis.
- Machine learning classification models.
- Advanced feature engineering.
- Interactive visualizations using Plotly.

## Author

Project created as part of a Titanic EDA learning exercise.

## License

This project is provided for educational purposes.
