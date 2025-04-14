# task-5-of-elevate-labs
#  Titanic Dataset - Exploratory Data Analysis (EDA)

This project is part of a Data Analyst Internship Task 5, focused on performing Exploratory Data Analysis (EDA) on the Titanic dataset using Python.

##  Objective

- Explore the Titanic dataset using Pandas, Matplotlib, and Seaborn.
- Visualize patterns, trends, and correlations.
- Handle missing data.
- Document observations and summarize insights in a clear, structured format.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

##  Steps Performed

1. **Data Loading**: Loaded the Titanic dataset (`train.csv`).
2. **Initial Exploration**: Used `.info()`, `.describe()`, `.isnull().sum()` to understand data structure and missing values.
3. **Data Cleaning**:
   - Filled missing values in `Age` with the median.
   - Filled missing values in `Embarked` with the mode.
   - Dropped the `Cabin` column due to excessive missing data.
4. **Univariate Analysis**: Plotted histograms and count plots for single variable insights.
5. **Bivariate Analysis**: Analyzed survival rates by gender, class, and fare using boxplots and violin plots.
6. **Correlation Analysis**:
   - Created a heatmap to check correlation among numerical features.
   - Used a pairplot to explore multivariate relationships.
7. **Summary**: Documented key insights and observations from the visual and statistical analysis.

##  Files Included

- `Titanic_EDA_Task5.ipynb`: Jupyter Notebook with complete analysis.
- `Titanic_EDA_Task5.pdf`: Exported version of the notebook.
- `train.csv`: The dataset used for analysis.
- `README.md`: You are here.

##  Key Insights

- Females had a significantly higher survival rate.
- Passengers in 1st class were more likely to survive.
- Passengers who paid higher fares also had better chances of survival.
- Children and younger adults had slightly better survival rates.
- Dataset is now clean and ready for modeling or advanced analytics.


## 🔗 Dataset Source

- [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic/data)

