# classification-challenge
Module 13 Challenge


# Spam Detector

This repository contains a Jupyter Notebook that demonstrates how to build and evaluate two machine learning models for detecting spam emails: a Logistic Regression model and a Random Forest Classifier. The dataset used in this project is sourced from the UCI Machine Learning Library.

## Table of Contents
- [Spam Detector](#spam-detector)
  - [Table of Contents](#table-of-contents)
  - [Dataset](#dataset)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Project Structure](#project-structure)
  - [Model Performance](#model-performance)
  - [Conclusion](#conclusion)

## Dataset

The dataset used in this project can be found at the following URL:
[Spam Data](https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv)

## Installation

To run this project, you need to have the following packages installed:

- pandas
- scikit-learn

You can install these packages using pip:

```bash
pip install pandas scikit-learn
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/spam-detector.git
cd spam-detector
```

2. Open the Jupyter Notebook:

```bash
jupyter notebook Spam_Detector.ipynb
```

3. Follow the instructions in the notebook to load the data, train the models, and evaluate their performance.

## Project Structure

- `Spam_Detector.ipynb`: The main Jupyter Notebook containing the code and analysis.

## Model Performance

Two models were created and compared:

1. **Logistic Regression Model**
    - Training Score: 0.9258
    - Accuracy: 0.9227

2. **Random Forest Classifier Model**
    - Training Score: 0.9994
    - Accuracy: 0.9583

## Conclusion

As predicted, the Random Forest model outperformed the Logistic Regression model. Below are the results:

- **Logistic Regression**
  - Training Score: 0.9257971014492754
  - Accuracy: 0.9226759339704604

- **Random Forest**
  - Training Score: 0.9994202898550725
  - Accuracy: 0.9582971329278888

The Random Forest model, while achieving a near-perfect training score, also showed better generalization with higher test accuracy. This indicates its effectiveness in classifying spam emails accurately.

### Author
This code was written by [Richard Lankford](https://github.com/rwlankford/classification-challenge) with assistance and review from **Rimi Sharma** and **Tyler B. Shubert**

###Resources
The dataset used in this project can be found at the following URL:
[Spam Data](https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv)

The spam data above was modified by edX Boot Camps LLC, and is intended for educational purposes only.

