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

## Concepts Refreshed

- Mean: Statistical average obtained by dived the sum of values by the no. of values
- Median: The middle-most value in the dataset once the data is arranged in ascending order
- Mode: Most frequentlu ocurring data
- Range: Maximum value - Minimum value
- Standard deviation (std): How spread out are the values from the mean. Describes the variability of the data. (low std: more simialr, high std: more variable)
- Variance: square of std
- Quartiles: Obtained by dividing the data into 4 parts, each representing 25% of the data.
  - Q1 (median of lower half): 25% of values exist below this
  - Q2 (median of entire data): 50% of the data are below this value
  - Q3 (median of upper half): 75% of values exist below this
- Interquartile range (IQR): Q3-Q1, shows the spread of the middle 50% of data
- Outliers: Values deviating significantly from most data

  
## Key Findings

- The dataset had 768 patient records and 9 clinical variables.
- There were no formally missing values at first glance, but several columns contained invalid zero values.
- Missing or invalid values were handled using median imputation.
- Glucose appeared to be one of the clearest visible differences between outcome groups.
- BMI also appeared higher in the diabetes-positive group, though with more overlap.
- The dataset suggests that diabetes outcome is influenced by multiple clinical factors rather than a single variable.
  
