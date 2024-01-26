# Heart Dataset Exploratory Data Analysis

## Overview

This project focuses on conducting Exploratory Data Analysis (EDA) on the Heart Dataset using Python. The analysis is performed in Jupyter Notebook, leveraging popular data manipulation and visualization libraries such as NumPy, Pandas, Matplotlib, and Seaborn.

## Project Description

The primary objective of this project is to gain insights into the Heart Dataset by performing EDA. The process involves checking for null and duplicated values to enhance data integrity. The steps include data cleaning and the utilization of various visualization techniques such as heatmap, countplot, distplot, boxplot, histogram, and facetgrid from Seaborn and Matplotlib.

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn

## Project Workflow

1. Import necessary libraries:

    ```python
    import pandas as pd
    import numpy as np
    import matplotlib.pyplot as plt
    import seaborn as sns
    ```

2. Read the dataset and create a duplicate dataset for safety:

    ```python
    o_data=pd.read_csv('Heart.csv')
    data=o_data.copy()
    ```

3. Conduct EDA using various functions from Pandas and NumPy, along with visualizations using Seaborn and Matplotlib:


## Key Insights

1. Out of 100% of individuals, approximately 46.67% (47%) have heart-related diseases, indicating a significant prevalence.

2. The dataset comprises 96 females and 206 males, with 70% of females and 45% of males experiencing heart-related issues.

3. The majority of individuals fall within the age group of 45 to 70.

4. Chest pain analysis reveals that the most common type is typical angina.

5. A noteworthy finding is that even among individuals without heart problems, a substantial number still experience chest pain.

6. An analysis of fasting blood sugar levels indicates a potential risk of diabetes.

7. Hypertension is suggested by a majority of individuals having blood pressure over 130 mm Hg.

8. Around half of the individuals have cholesterol levels exceeding 240 mm/dl, considered high.

## Recommendations

Based on the analysis, the following recommendations are suggested:

- Individuals with typical angina chest pain should undergo further evaluation for potential heart-related issues.
- Regular monitoring of fasting blood sugar levels is crucial, especially for those with imbalances.
- Lifestyle modifications, including dietary changes, may be beneficial for individuals with high blood pressure or cholesterol levels.

## Conclusion

This EDA provides valuable insights into the Heart Dataset, highlighting patterns and potential risk factors associated with heart-related issues.

## Contact

- **Shailesh Jain**
  - GitHub: [shaileshjain28](https://github.com/shaileshjain28)
  - Email: [jainshailesh028@gmail.com](mailto:jainshailesh028@gmail.com)
  - LinkedIn: [Shailesh Jain](https://www.linkedin.com/in/shailesh-jain-1297251ab/)
