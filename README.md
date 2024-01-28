# Sampling

## Introduction

This project explores the impact of various sampling techniques on the performance of different machine learning algorithms. The focus is on understanding how sampling methods can address class imbalance in datasets and influence the accuracy of models.

## Sampling Techniques

The following sampling techniques are employed to address class imbalance:

1. **Random Under Sampling (RUS):** Randomly removes samples from the majority class to balance the class distribution.

2. **Random Over Sampling (ROS):** Randomly duplicates samples from the minority class to balance the class distribution.

3. **SMOTE (Synthetic Minority Over-sampling Technique):** Generates synthetic samples for the minority class to achieve balance.

4. **NearMiss:** Selects samples from the majority class based on their proximity to minority class samples.

5. **Systematic Sampling:** A systematic subsample of the majority class is created by selecting every k-th element.

## Sample Size Calculation

The sample size for each sampling technique is calculated using the formula:

![Sample Size Formula](/Sampling/formula.png)

where Z is the z-value, p is the estimated proportion of the majority class, and E is the desired margin of error.

## Machine Learning Models

The experiment involves training the following machine learning models:

1. **Logistic Regression**
2. **Decision Tree**
3. **Random Forest**
4. **Support Vector Machine (SVM)**
5. **K-Nearest Neighbors (KNN)**


## Conclusion

The project concludes with a summary of findings, highlighting the impact of sampling on model performance and offering insights into the most effective combinations of sampling techniques and classifiers for the given dataset.

![Results](/Sampling/Results.png)