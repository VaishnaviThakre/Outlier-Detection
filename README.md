

# Outlier Detection in Iris Dataset

Welcome to the Outlier Detection project! This repository contains Python code for detecting outliers in the famous Iris dataset using the Interquartile Range (IQR) method. Below, you'll find a detailed explanation of the project, including setup instructions, code details, and visualizations of the results.

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Setup Instructions](#setup-instructions)
4. [Results](#results)
5. [Summary](#summary)
6. [Contributing](#contributing)
7. [License](#license)

## Introduction

This repository contains code for detecting outliers in the Iris dataset using the Interquartile Range (IQR) method. Outliers can significantly affect the performance of machine learning models, and detecting them is a crucial step in data preprocessing.

Outlier detection is an essential step in data preprocessing, as it helps in identifying and possibly removing anomalous data points that can skew the analysis. This project focuses on detecting outliers in the Iris dataset using the IQR method and visualizing the results with box plots.

## Dataset

The Iris dataset used in this project is publicly available and can be found here. The dataset consists of 150 samples from each of three species of Iris flowers (Iris setosa, Iris versicolor, and Iris virginica). Four features were measured from each sample: sepal length, sepal width, petal length, and petal width.

## Setup Instructions

To get started, follow these instructions to set up your environment:

1. **Clone the Repository**:
    ```sh
    git clone git@github.com:VaishnaviThakre/Outlier-Detection.git
    cd Outlier-Detection
    ```

2. **Install Dependencies**:
    Make sure you have Python and pip installed. Then, run:
    ```sh
    pip install pandas numpy matplotlib seaborn
    ```

## Results

The output of the outlier detection process includes visualizations and summaries of outliers for each feature in the dataset. Below are some key observations:


### Sepal Length
- **No outliers**: All data points are within the expected range.

### Sepal Width
- **Outliers identified**:
  - Three instances of *Iris-setosa*:
    - Index 15: Sepal width of 4.4
    - Index 32: Sepal width of 4.1
    - Index 33: Sepal width of 4.2
  - One instance of *Iris-versicolor*:
    - Index 60: Sepal width of 2.0

### Petal Length
- **No outliers**: All data points are within the expected range.

### Petal Width
- **No outliers**: All data points are within the expected range.

## Summary

- **Outliers in Sepal Width**: Primary outliers are in the sepal width, with a few *Iris-setosa* instances having higher values and one *Iris-versicolor* instance having a lower value.
- **No Outliers in Other Features**: Sepal length, petal length, and petal width do not have significant outliers according to the IQR method.

## Contributing
We welcome contributions to improve this project. If you have suggestions for improvements or want to add new features, please open an issue or create a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

Thank you for using our outlier detection tool!!I hope it helps you in your data analysis and preprocessing tasks.

