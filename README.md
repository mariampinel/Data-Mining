# Data Mining Course Assignment QMUL 
This repository contains the code and analysis for the course assignment in Data Mining. The assignment involves various data manipulation, analysis, and visualization tasks using Python and its libraries such as pandas, matplotlib, and scikit-learn. Below is an overview of each task covered in the final report, which demonstrates the steps taken to analyze and manipulate datasets.

## Project Overview
### Task 1: Wine Dataset Analysis

**Data:** The wine dataset from sklearn.datasets is loaded and analyzed.

**Objectives:** Categorical Feature Identification: Identify and compute the frequency of the categorical feature.
- Univariate and Multivariate Summaries: Generate two univariate and two multivariate summaries for numerical features.
- Grouping by Categorical Feature: Group observations by the categorical feature and compute the corresponding median for each numerical feature.
- Scatter Plot: Create a scatter plot for the pair of numerical features with the highest correlation.

### Task 2: Binning Techniques on Sales Data

**Data:** A simple sales dataset.

**Objectives:** 
- Apply equal-frequency binning and smoothing by bin boundaries to the data, dividing it into 3 bins and comparing the results.

### Task 3: Data Cleaning and Transformation

**Data:** The country-income.csv file containing both numerical and categorical features.

**Objectives:** 
- Clean the data by replacing missing values (NaNs) with the mean of each feature.
- Convert categorical features into numerical values using sklearn.preprocessing.
- Display the resulting cleaned dataset.

### Task 4: Shoe Size and Height Analysis

**Data:** The shoesize.csv file contains shoe size and height measurements.

**Objectives:** 
- Plot scatter plots of shoe size vs. height for male and female subjects separately.
- Compute the Pearson correlation coefficient for both genders and discuss the relationship between shoe size and height based on the scatter plots and correlation results.

### Task 5: Principal Component Analysis (PCA) on Wine Dataset

**Data:** The wine dataset.

**Objectives:** 
- Perform PCA with two components and visualize the data along the principal components.
- Analyze how well the classes (target variable) are distinguishable in the scatterplot of the principal components.
- Discuss the issue of class overlap and perform a preprocessing step to improve PCA results.

### Task 6: Interpretation of Heatmap (Pen-and-Paper)

**Data:** graduation_rate.csv dataset.

**Objectives:** 
- Explain how the distance matrix heatmap helps infer the relationship between students with different parental education levels.

### Task 7: Data Cube and Aggregation

**Data:** country-income.csv.

**Objectives:** 
- Use Cubes to create a data cube model with dimensions for region, age, and online shopping activity, and a measure for income.
- Perform aggregation operations (total, average, min, max) on the data cube and produce results per region, online shopping activity, and age group (40-50).

### Task 8: Nearest Neighbor Classifier
**Data:** A simple 2-observation dataset.

**Objectives:** 
Classify new observations using a 1-nearest neighbor classifier based on Euclidean distance and explain the classification process.

### Final Report
The final report includes:

- Detailed explanations of each task with the corresponding code in Python (no screenshots).
- Visualizations (e.g., scatter plots, PCA plots, heatmaps) to support the analysis.
- Results of statistical tests (e.g., Pearson correlation, PCA analysis).
- Interpretation and conclusions based on the datasets and analysis methods applied.

All code and analysis steps are provided in the repository, including all necessary comments and explanations.
