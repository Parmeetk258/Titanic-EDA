# Titanic-EDA
Exploratory Data Analysis (EDA) on the Titanic dataset using Python, Pandas, Matplotlib , and Seaborn to analyze data, identify patterns, and visualize key insights.
# 🚢 Titanic Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset using Python. The objective is to understand the dataset, identify missing values, analyze key features, and discover patterns related to passenger survival through statistical summaries and visualizations.

## 🎯 Objective
- Explore the Titanic dataset.
- Understand the structure and quality of the data.
- Identify missing values and descriptive statistics.
- Analyze survival and gender distribution.
- Visualize relationships between important features.

## 🛠️ Tools & Libraries
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook (VS Code)

## 📂 Dataset
- Titanic Dataset (`titanic.csv`)

## 📊 Exploratory Data Analysis Performed
- Imported required libraries
- Loaded and previewed the dataset
- Displayed dataset information (`info()`)
- Generated summary statistics (`describe()`)
- Checked missing values
- Analyzed survival distribution
- Analyzed gender distribution
- Created Pair Plot
- Generated Correlation Heatmap
- Plotted Histogram
- Created Box Plot
- Created Scatter Plot

## 📈 Key Findings
- The dataset contains missing values, mainly in the **Age**, **Cabin**, and **Embarked** columns.
- Most passengers did not survive the disaster.
- Male passengers outnumbered female passengers.
- The **Fare** column contains several outliers.
- Most passengers were between **20 and 40 years** of age.
- Passenger class and fare showed a stronger relationship with survival than age.

## 📁 Repository Structure
```
Titanic-EDA/
│── EDA.ipynb
│── titanic.csv
│── Titanic_EDA_Report.pdf
│── README.md
```

## ▶️ How to Run
1. Clone the repository.
2. Open `EDA.ipynb` in VS Code or Jupyter Notebook.
3. Install the required libraries:
   ```
   pip install pandas matplotlib seaborn
   ```
4. Run all cells in the notebook.

## ✅ Conclusion
This project demonstrates the fundamentals of Exploratory Data Analysis using Python. Through statistical summaries and visualizations, meaningful insights were extracted from the Titanic dataset, helping to better understand passenger characteristics and survival patterns.
