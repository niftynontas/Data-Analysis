# Data-Analysis

Overview
This project performs basic data analysis and visualizations on the dataset DIA_testset_RDKit_descriptors.csv. The dataset contains molecular descriptors, including molecular weight (MolWt) and other features relevant to chemical analysis.

The following tasks were performed:

Loading and Exploring the Dataset: The dataset was loaded, and its structure was explored to identify missing values and data types. Missing data was handled by dropping rows with missing values.

Basic Data Analysis: Descriptive statistics, median, and standard deviation were computed for the numerical columns to gain insights into the data's central tendency and spread.

Data Visualization:

A line chart was created to visualize the trend of molecular weight (MolWt) over the dataset's index.

A bar chart was plotted to compare the average molecular weight across categories (i.e., by label).

A histogram was used to visualize the distribution of molecular weight.

A scatter plot was generated to analyze the relationship between molecular weight (MolWt) and topological polar surface area (TPSA).

Instructions
Ensure the dataset DIA_testset_RDKit_descriptors.csv is in the working directory.

The script is compatible with Jupyter Notebook. It uses Pandas, Matplotlib, and Seaborn libraries for data manipulation and visualization.

If any required column like "Label" or "TPSA" is missing, the code handles it gracefully by skipping the corresponding visualizations.

Libraries Used:
pandas for data manipulation.

matplotlib and seaborn for data visualization.

Conclusion
This project demonstrates the application of basic data analysis techniques, including data exploration, descriptive statistics, and visualizations, to gain insights from the molecular descriptor dataset. The visualizations help in understanding patterns in molecular weight and its relationship with other features in the dataset.
