# Uterine-Cancer
# Machine Learning Model Deployment with Dash

This repository contains code for deploying a machine learning model using Dash. The model, in this case, is a Random Forest classifier trained on a dataset related to uterine cancer.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project demonstrates how to deploy a machine learning model using Dash, a web application framework for Python. The Random Forest model is trained on a dataset related to uterine cancer, and the web interface allows users to input features for prediction.

## Dataset

The dataset used in this project contains information about uterine cancer, including features such as mutation count, fraction genome altered, diagnosis age, and more. The target variable is disease-specific survival status.

**Dataset Columns:**
- Cancer Type
- Overall Survival Status
- Disease Free Status
- Disease-specific Survival Status
- Mutation Count
- Fraction Genome Altered
- Diagnosis Age
- MSI MANTIS Score
- MSIsensor Score
- Race Category
- Subtype
- Tumor Type

## Prerequisites

Ensure you have the following installed in your environment:
- Python (>=3.6)
- Dash
- pandas
- scikit-learn
- imbalanced-learn

Install the required packages using:

```bash
pip install dash pandas scikit-learn imbalanced-learn
