# ITAI-1371 Introduction to Machine Learning

## Lab 11: Hyperparameter Tuning and AutoML

**Student:** Delores Bledsoe
**Course:** ITAI-1371 Introduction to Machine Learning
**Lab:** Hyperparameter Tuning and AutoML

---

## Overview

This lab focuses on improving machine learning model performance through **hyperparameter tuning** and exploring the concept of **Automated Machine Learning (AutoML)**.

Machine learning algorithms often include settings called hyperparameters that control how a model learns. Selecting the right hyperparameters can improve accuracy, reduce errors, and help models generalize better to new data.

AutoML extends this process by automating parts of the machine learning workflow, including model selection, parameter optimization, and evaluation.

---

## Lab Objectives

By completing this lab, I learned how to:

* Understand the role of hyperparameters in machine learning models.
* Distinguish between model parameters and hyperparameters.
* Apply hyperparameter tuning techniques.
* Use validation methods to compare model performance.
* Optimize machine learning models for better results.
* Understand the purpose and benefits of AutoML.
* Evaluate improved model performance after tuning.

---

# Hyperparameter Concepts

## What Are Hyperparameters?

Hyperparameters are settings chosen before training a machine learning model. They control how the algorithm learns from data and can significantly affect model performance.

Examples of hyperparameters include:

* Number of trees in a Random Forest.
* Maximum depth of a Decision Tree.
* Learning rate in boosting algorithms.
* Number of neighbors in K-Nearest Neighbors.

Unlike model parameters, which are learned automatically during training, hyperparameters must be selected and adjusted by the developer.

---

# Hyperparameter Tuning

Hyperparameter tuning is the process of testing different combinations of hyperparameter values to find the settings that produce the best model performance.

The goal of tuning is to:

* Improve prediction accuracy.
* Reduce overfitting.
* Improve model generalization.
* Create more reliable machine learning models.

---

## Grid Search

Grid Search tests a defined set of hyperparameter combinations and selects the combination that produces the best results.

Advantages:

* Thorough search of possible combinations.
* Easy to understand and implement.

Limitations:

* Can require significant computational resources.
* Becomes slower with many hyperparameters.

---

## Random Search

Random Search tests randomly selected combinations of hyperparameters.

Advantages:

* Faster than Grid Search for large search spaces.
* Can find effective combinations with fewer tests.

Limitations:

* Does not test every possible combination.

---

# Cross-Validation

Cross-validation is used during tuning to provide a more reliable estimate of model performance.

Instead of evaluating a model using only one train/test split, cross-validation:

* Divides the data into multiple sections.
* Trains and evaluates the model multiple times.
* Produces a more dependable performance estimate.

---

# AutoML Concepts

## What Is AutoML?

Automated Machine Learning (AutoML) uses automated processes to simplify machine learning development.

AutoML can help automate:

* Data preprocessing.
* Algorithm selection.
* Hyperparameter optimization.
* Model evaluation.

Benefits of AutoML include:

* Faster model development.
* Reduced manual experimentation.
* Improved accessibility for machine learning workflows.

---

# Machine Learning Workflow Used

This lab followed the optimization stage of the machine learning workflow:

### 1. Build Initial Model

A baseline machine learning model was created.

### 2. Evaluate Performance

The model was evaluated using appropriate metrics.

### 3. Tune Hyperparameters

Different hyperparameter settings were tested.

### 4. Compare Results

Performance before and after tuning was analyzed.

### 5. Select Improved Model

The best-performing model was identified based on evaluation results.

---

## Tools and Technologies Used

### Programming Language

* Python

### Development Environment

* Jupyter Notebook / Google Colab

### Libraries Used

* **NumPy** – Numerical computing
* **Pandas** – Data manipulation and analysis
* **Matplotlib** – Visualization
* **Seaborn** – Statistical visualization
* **Scikit-learn** – Machine learning models and tuning tools

---

## Lab Requirements Completed

The notebook was completed by working through all required sections, including:

### Code Sections

Completed tasks involving:

* Training machine learning models.
* Defining hyperparameters.
* Applying tuning techniques.
* Comparing model performance.
* Selecting optimized models.

### Explanation Sections

Completed written analysis covering:

* Hyperparameter importance.
* Model improvement strategies.
* Tuning results.
* AutoML concepts.

### Knowledge Checks

Answered embedded questions demonstrating understanding of:

* Parameters versus hyperparameters.
* Model optimization.
* Cross-validation.
* Automated machine learning.

### Reflection Questions

Completed reflections discussing:

* The impact of tuning on model performance.
* Benefits and limitations of AutoML.
* How optimization improves machine learning workflows.

---

## Repository Contents

```text
Lab11_Hyperparameter_Tuning_AutoML/

│
├── README.md
│
└── Lab11_Hyperparameter_Tuning_AutoML.ipynb
```

---

## Skills Demonstrated

Through this lab, I practiced:

* Improving machine learning models through optimization.
* Applying Grid Search and Random Search techniques.
* Using cross-validation for model evaluation.
* Understanding automated machine learning workflows.
* Comparing baseline and optimized models.
* Documenting machine learning experiments.

---

## What I Learned

This lab demonstrated that building a machine learning model is an iterative process. A model's initial performance can often be improved by selecting better hyperparameters and evaluating different configurations.

I learned that AutoML can simplify parts of the machine learning process by automating repetitive tasks, while understanding the fundamentals of tuning remains important for making informed modeling decisions.

---

## Conclusion

The Hyperparameter Tuning and AutoML lab provided practical experience improving machine learning models through optimization techniques. These skills are important for developing accurate, efficient, and reliable machine learning solutions.

---

## Author

**Delores Bledsoe**
ITAI-1371 Introduction to Machine Learning

