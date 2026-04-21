# From Clinical to Data

This project is my first step toward understanding healthcare from a data-driven perspective.

Coming from a clinical background, I wanted to explore how patterns in medical data can be observed, interpreted, and understood using basic tools in Python. This repository represents the beginning of that transition.

## Objective

In this project, I will be working with a simple healthcare dataset and learning how to:

- load and explore data using Python
- clean and organize raw information
- identify basic patterns and trends
- visualize key insights

## Introduction

During my medical training, I became increasingly interested in understanding the underlying patterns behind clinical observations. At the same time, I realized that I wanted to engage with healthcare in a way that was more analytical and less dependent on direct patient interaction.

This project is part of my effort to move in that direction, while building a foundation in data analysis and bioinformatics.

## Tools Involved

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## Steps Involved

- Choose a healthcare dataset
- Perform initial data exploration
- Create simple visualizations
- Document observations

## Key Findings
- The dataset had 768 patient records and 9 clinical variables
- There were no formally missing values at first glance, but several columns contained invalid zero values
- Missing or invalid values were handled using median imputation
- Glucose value appears to be one of the strongest visible differences between outcome groups
- BMI also appears higher in the diabetes-positive group, though likely with more overlap
- The dataset suggests diabetes outcome is influenced by multiple clinical factors and not just one.
