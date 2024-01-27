# Blood Donation Prediction System

## Overview

This repository contains the code for a system that predicts the likelihood of a person making a blood donation based on features such as name, blood group, and city. It leverages machine learning with a Naive Bayes algorithm and offers a user-friendly interface for real-time predictions.

## Table of Contents

Installation: #installation

Usage: #usage

Optimized Code: #optimized-code

Model Comparison: #model-comparison

Demo: #demo

Output Screenshots: #output-screenshots

## Installation

1. Clone the repository:
   
git clone https://github.com/your-username/blood-donation-prediction.git
cd blood-donation-prediction

2. Install the required dependencies:
   
```pip install -r requirements.txt```

## Usage

1. Open the Jupyter notebook Final_Intel_prj.ipynb.
2. Follow the instructions and run the cells to:
   
      *Explore the data
   
      *Train the machine learning model
   
      *Launch the Gradio interface for real-time predictions
## Optimized Code

The code is optimized using Intel OneAPI for enhanced performance. Key optimizations include:

Patching Scikit-learn with Intel extensions:

```from sklearnex import patch_sklearn```
```patch_sklearn()```

## Model Comparison

We evaluated three machine learning models:

1. Naive Bayes (chosen, accuracy 0.75)

2. Logistic Regression (accuracy 0.74)

3. Random Forest (accuracy 0.71)

Based on these results, we chose Naive Bayes as it provided the highest accuracy.


## Demo Video


https://github.com/mohamedbadus/Project_Intel/assets/116250693/7ba7dd62-19ef-4932-9517-72b05e913047



## Output Screenshots

![Screenshot 2024-01-27 104257](https://github.com/mohamedbadus/Project_Intel/assets/116250693/203f8554-cd6c-4347-8810-7bcdbb608275)

![Screenshot 2024-01-27 104314](https://github.com/mohamedbadus/Project_Intel/assets/116250693/1a0b620a-1a5c-4922-8c5a-56e19a3907ae)
