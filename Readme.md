# Mall Customer Segmentation with K-means Clustering

## Table of Contents

- [Introduction](#introduction)

- [Project Overview](#project-overview)

- [Methodology](#methodology)

- [Data](#data)

- [Usage](#usage)

- [My Contributions](#my-contributions)

  

## Introduction

Welcome to the Mall Customer Segmentation project repository! Customer segmentation is the process of dividing customers into groups based on shared characteristics. This project aims to analyze customer data from a mall and segment customers using the K-means clustering algorithm. By comprehending customer segments, malls and retailers can tailor marketing strategies and services more effectively.

## Project Overview

- Team: 5 people
- Programming Languages: R programming
- Libraries/Frameworks: corrplot, readr, naniar, ggplot2, plotrix, cluster, factoextra, fpc, scatterplot3d, etc
- Date: Fall 2022
- Status: Completed

## Methodology

- **Data Collection**: Describe how you collected the data for the project.
- **Data Preprocessing**: Explain data cleaning, feature selection, and any transformations performed.
- **K-means Clustering**: Detail the implementation of the K-means clustering algorithm, including the choice of the number of clusters (K).

## Data

- **Source**: Mall_Customers.csv

- **Data Files**: ./MallCustomerSegmentation/data

- **Data Description**: 

  | Feature                | Description                                                  |
  | ---------------------- | ------------------------------------------------------------ |
  | CustomerID             | An identifier for each customer.                             |
  | Gender                 | The gender of the customer.                                  |
  | Age                    | The age of the customer.                                     |
  | Annual Income (k$)     | The annual income of the customer in thousands of dollars.   |
  | Spending Score (1-100) | A spending score assigned to the customer, typically ranging from 1 to 100, representing their spending behavior. |

  

## Usage

- **Installation**: 

  ```
  # Example commands or code snippets for running the project
  $ git clone [repository URL]
  $ cd mall-customer-segmentation
  ```

  

  ```
  install.packages("corrplot")
  install.packages("readr")
  install.packages("naniar")
  install.packages("ggplot2")
  install.packages("plotrix")
  install.packages("cluster")
  install.packages("factoextra")
  install.packages("fpc")
  install.packages("scatterplot3d")
  ```

  > Import the code to RStudio

- **Notebooks/Scripts**: Mall_Customers_Analysis.Rmd

- **Parameters/Configuration**: N/A



## My Contributions

As a key member of the project team, I played a pivotal role in various aspects of the project, contributing significantly to its success. My responsibilities encompassed:

1. Data Cleaning and Preprocessing: I meticulously ensured the dataset's accuracy and consistency. This involved identifying and rectifying missing or erroneous data, handling duplicates, and standardizing data formats. By carefully curating the dataset, I laid a strong foundation for meaningful analysis.

2. Feature Engineering: I was actively involved in the process of selecting and creating relevant features from the raw data. This involved transforming and engineering variables that provided valuable insights into customer behavior. The feature engineering phase played a crucial role in improving the performance of machine learning models.

3. Machine Learning Model Selection and Training: I undertook the task of identifying suitable machine learning models for customer segmentation. This process involved researching various algorithms, selecting those best suited to our dataset, and fine-tuning hyperparameters to optimize model performance. We selected and trained seven machine learning models, ensuring that each model was well-suited to the specific task of customer segmentation.

