# Data Cleaning Approach for nhgh Dataset

## Objective
The objective of this document is to outline the approach for cleaning and preparing the "nhgh" dataset for further analysis and modeling.

## Approach Overview
The following steps will be followed to clean and preprocess the "nhgh" data:

1. **Exploration and Descriptive Statistics**
   - Explore the "nhgh" dataset to understand its structure, features, and basic statistics.
   - Perform descriptive statistics to gain insights into the data distribution.

2. **Database Relation and Design**
   - Utilize sqlite3 to create a relational database for efficient data management.
   - Design tables and relationships based on the "nhgh" dataset schema.

3. **Visualizing Feature Distributions**
   - Visualize feature distributions from the "nhgh" dataset using appropriate plots like histograms, box plots, and scatter plots.
   - Identify outliers and anomalies in the "nhgh" data.

4. **Data Transformation**
   - Perform necessary alterations on specific columns such as "income" and "gh" in the "nhgh" dataset to ensure data consistency and accuracy.
   - Handle data encoding, scaling, or normalization as required.

5. **Handling Null Values**
   - Conduct a basic exploration of null values in the "nhgh" dataset.
   - Decide on strategies for handling missing data, such as imputation or removal.

6. **Pipeline Steps for Training**
   - Define preprocessing steps and data transformations as part of a pipeline for model training using the "nhgh" data.
   - Ensure compatibility with machine learning algorithms and frameworks.

7. **Discussion of Results**
   - Summarize the outcomes of data cleaning and preprocessing for the "nhgh" dataset.
   

## Conclusion
Our final chosen model was randomforestclassifier after gridsearching. Refer to the notebook for detailed information.
