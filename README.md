# Iris-Analysis-SQL-Pandas
# Iris Dataset Analysis: SQL + Pandas

## Project Overview

This project explores the Iris dataset using SQL for structured querying and Pandas for further processing & visualization. The goal is to analyze species differentiation based on petal and sepal characteristics and demonstrate a combination of database querying and Python-based analysis.

## Dataset Details

- Name: Iris Species
- Link: [Kaggle](https://www.kaggle.com/datasets/uciml/iris)

#### Attributes:

sepal_length, sepal_width, petal_length, petal_width

species (Setosa, Versicolor, Virginica)

## Objective
*The objective of this analysis is to explore the Iris dataset to:*

- Are there any missing or inconsistent values in the dataset?
- Understand the distribution of petal and sepal sizes across different species.
- Identify patterns and relationships between features using visualizations.
- Detect similarities and differences among the three Iris species.
- Which features best distinguish the three species?

## Workflow

1. SQL

- Load the dataset into MySQL

- Perform data cleaning (handle nulls, duplicates, outliers)

- Generate summary statistics

- Extract insights through queries

2. Pandas & Visualization

- Connect MySQL with Pandas for further analysis

- Perform exploratory data analysis (EDA)

- Visualize patterns and relationships between features


### Key Insights

- Setosa is the most distinct species due to its small petal size and wide sepals.

- Petal length and width are the best features for classification (high correlation).

- Sepal width does not contribute much to distinguishing species.

- Versicolor and Virginica have some overlap, but Virginica has generally larger petal sizes.

### Conclusion

This project showcases SQL for structured querying and Pandas for deeper analysis & visualization. 
