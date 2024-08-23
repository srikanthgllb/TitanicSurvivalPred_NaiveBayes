# TitanicSurvivalPred_NaiveBayes
# Titanic Survival Prediction using Naive Bayes

Welcome to the Titanic Survival Prediction project! This repository contains a machine learning model built with the Naive Bayes algorithm to predict passenger survival on the Titanic. 

## Project Overview

The Titanic disaster of 1912 remains one of the most infamous maritime tragedies in history. In this project, we aim to leverage historical passenger data to predict whether a passenger survived or not based on several features.

### Dataset

The dataset used in this project includes the following columns:

- **Pclass**: Passenger class (1, 2, or 3)
- **Gender**: Gender of the passenger (male or female)
- **Age**: Age of the passenger
- **Fare**: Ticket fare paid by the passenger
- **Survived**: Survival status (0 = No, 1 = Yes)

### Requirements
```bash
pandas==2.0.3
numpy==1.25.1
scikit-learn==1.3.2
matplotlib==3.8.0
```
### Model
We use the Naive Bayes algorithm, a simple yet effective classification technique, to predict survival outcomes. Naive Bayes is well-suited for this task due to its efficiency with categorical data and ability to handle multiple features.



### Features

- **Pclass**: Indicates the class of the passenger, which may correlate with survival chances.
- **Gender**: Gender-based survival trends are known to influence survival rates.
- **Age**: Age can impact survival probability, with different age groups having varying survival rates.
- **Fare**: The fare paid may reflect socio-economic status, which can affect survival chances.

### Installation

To get started with the project, clone this repository and install the necessary dependencies:

```bash
git clone [https://github.com/srikanthgllb/TitanicSurvivalPred_NaiveBayes/tree/main]
pip install -r requirements.txt
