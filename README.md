# Data Science Project: VGsales Analysis

**Description:**  
This project focuses on analyzing the VGsales dataset, which comprises global video game sales data. The dataset includes information on over 16,500 video games, such as their release year, genre, platform, publisher, and sales figures in various regions. The objective is to perform data cleaning, analysis, visualization, and create a dashboard using Power BI.

---

## Table of Contents
1. [Introduction](#introduction)
2. [Data Cleaning](#data-cleaning)
3. [Visualization](#visualization)
4. [Machine Learning](#machine-learning)
5. [Installation](#installation)
6. [Usage](#usage)


---

## Introduction
The VGsales dataset is a collection of video game sales data from around the world. It contains information on over 16,500 video games, including their release year, genre, platform, publisher, and sales figures in North America, Europe, Japan, and the rest of the world, as well as global sales figures. This dataset is often used by researchers, analysts, and enthusiasts to study trends in the video game industry, such as the popularity of certain game genres, the success of different gaming platforms, and the impact of various factors on game sales.

## Data Cleaning
Data cleaning is the process of identifying and correcting or removing errors, inconsistencies, and inaccuracies in a dataset. This process is essential to ensure that the data is accurate, complete, and consistent for effective analysis and modeling.

1. **Missing Values:**  
   In this project, I handled missing values by using imputation methods to fill in gaps where possible, and I removed rows with excessive missing data to ensure the integrity of the dataset.

2. **Data Types:**  
   I ensured that each column in the dataset had the correct data type. For instance, I converted the 'Year' column to a numerical format and ensured categorical variables such as 'Genre' and 'Platform' were treated as categorical data types.

3. **Duplicates:**  
   I identified and removed duplicate entries from the dataset using the `drop_duplicates()` function in pandas to ensure that each game was represented only once.

4. **Handling Outliers:**  
   I used statistical methods to identify outliers in sales figures, such as the IQR method, and decided to handle them by either removing them or transforming them based on their impact on the analysis.

## Visualization
Visualization refers to the representation of data or information in a graphical or pictorial format. The goal is to help people understand and interpret complex data by presenting it in a way that is easy to understand and visually appealing.

In this project, I created various visualizations to illustrate trends and patterns in the data:
![PowerPi](https://github.com/Basmaaashraf/Data-science-project/blob/main/virsualization.jpg)


## Machine Learning
Machine learning is a subfield of artificial intelligence that involves training algorithms to learn patterns and insights from data without being explicitly programmed.

1. **Regression:**  
   I applied linear regression techniques to predict video game sales based on features such as genre, platform, and year of release. This allowed me to estimate the sales potential of new games based on historical data.

2. **Classification:**  
   I utilized classification methods, such as decision trees, to categorize games into different genres based on their features, helping to identify trends in genre popularity over time.

## Installation
To set up the environment for this project, ensure you have Python installed. Then, run the following commands to install the necessary libraries:

```bash
pip install pandas matplotlib seaborn scikit-learn
```
## usage 

To preprocess the data and conduct the analysis, follow these steps:

 **Clone the Repository**:  
   First, clone the repository to your local machine using the following command:

   ```bash
   git clone https://github.com/basmaashraf/Data-Science-Project.git
   cd vgsales-analysis

