📌 Project Overview

This project performs a beginner-friendly Exploratory Data Analysis (EDA) on the Titanic dataset.
The goal is to understand key patterns in the data, clean missing information, visualize important features, and summarize findings using basic statistical and graphical techniques.

📂 Dataset

The dataset contains passenger details such as:

- Age

- Gender

- Passenger class

- Fare

- Number of family members

- Survival status

It is a publicly available dataset commonly used for learning data analysis.

🛠️ Technologies Used

- Python

- Pandas

- Matplotlib

- Seaborn

- Jupyter Notebook

📌 Steps Performed
1. Data Loading

- The dataset was imported into a Pandas DataFrame for inspection and processing.

2. Data Cleaning

- Missing values in Age were filled using the average age.

- Missing values in Embarked were filled using the most common entry.

- The Cabin column was removed due to many missing values.

- Duplicate rows were checked and removed.

3. Exploratory Analysis

- Basic statistics were generated to understand numerical features.

- Visualizations such as histograms, count plots, and boxplots were created.

- Relationships between variables were studied using grouped plots and correlation heatmaps.

4. Visualization

- Matplotlib and Seaborn were used to create simple and clear charts, including:

- Age distribution

- Passenger gender counts

- Survival comparison by gender

- Age vs. survival patterns

- Correlation heatmap for numeric features

5. Key Insights

- Female passengers had a higher chance of survival.

- First-class passengers survived more frequently than other classes.

- Higher fares were generally linked with higher survival chances.

- Younger passengers tended to have slightly better outcomes.

6. Summary

The project highlights how demographic and economic factors played a major role in survival outcomes on the Titanic.
Through data cleaning and visualization, the analysis provides clear and easy-to-understand insights into the dataset.



🚀 How to Run the Project

Install dependencies:

pip install pandas matplotlib seaborn


Launch Jupyter Notebook:

jupyter notebook


Open the notebook file and run cells sequentially.