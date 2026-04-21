# From Clinical to Data

This project is my first step toward understanding healthcare from a data-driven perspective.

Coming from a clinical background, I wanted to explore how patterns in medical data can be observed, interpreted, and understood using basic tools in Python. This repository represents the beginning of that transition.

## Objective

In this project, I worked with a simple healthcare dataset to begin learning how to:

- load and explore data using Python
- clean and organize raw information
- identify basic patterns and trends
- visualize key insights

## Introduction

During my medical training, I became increasingly interested in understanding the underlying patterns behind clinical observations. At the same time, I realized that I wanted to engage with healthcare in a way that was more analytical and less dependent on direct patient interaction.

This project is part of my effort to move in that direction while building a foundation in data analysis and bioinformatics.

## Tools Involved

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## Steps Involved

- Choose a healthcare dataset
- Perform initial data exploration
- Clean and organize the data
- Create simple visualizations
- Document observations

## Concepts Revised

- **Mean**: The statistical average, obtained by dividing the sum of all values by the number of values.
- **Median**: The middle value in a dataset once the data is arranged in ascending order.
- **Mode**: The most frequently occurring value in the dataset.
- **Range**: Maximum value - Minimum value.
- **Standard deviation (std)**: Shows how spread out the values are from the mean. A low standard deviation means the values are closer together, while a high standard deviation means they are more spread out.
- **Variance**: The square of the standard deviation.
- **Quartiles**: Values that divide the data into 4 parts, each representing 25% of the dataset.
  - **Q1** (first quartile): 25% of the values fall below this point.
  - **Q2** (second quartile / median): 50% of the values fall below this point.
  - **Q3** (third quartile): 75% of the values fall below this point.
- **Interquartile range (IQR)**: Q3 - Q1. It shows the spread of the middle 50% of the data.
- **Outliers**: Values that differ significantly from the rest of the data.

  
## Key Findings

- The dataset had 768 patient records and 9 clinical variables.
- There were no formally missing values at first glance, but several columns contained invalid zero values.
- Missing or invalid values were handled using median imputation.
- Glucose appeared to be one of the clearest visible differences between outcome groups.
- BMI also appeared higher in the diabetes-positive group, though with more overlap.
- The dataset suggests that diabetes outcome is influenced by multiple clinical factors rather than a single variable.
  
