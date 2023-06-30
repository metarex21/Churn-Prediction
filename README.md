# Churn Predicton

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

A churn predictor is a machine learning model that helps identify customers who are likely to leave a business or stop using its services. This repository contains code and resources for developing a churn predictor.

## Dataset

This dataset contains customer data from a telecommunications company and is focused on predicting customer churn. The dataset provides information about customers' demographics, services subscribed, and churn status.

## Dataset Source

The dataset can be accessed from Kaggle at the following link:
[Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## Description

The Telco Customer Churn dataset consists of the following columns:

- `customerID`: Unique identifier for each customer
- `gender`: Customer's gender (Male/Female)
- `SeniorCitizen`: Indicates if the customer is a senior citizen (0: No, 1: Yes)
- `Partner`: Whether the customer has a partner (Yes/No)
- `Dependents`: Whether the customer has dependents (Yes/No)
- `tenure`: Number of months the customer has been with the company
- `PhoneService`: Whether the customer has a phone service (Yes/No)
- `MultipleLines`: Whether the customer has multiple lines (Yes/No/No phone service)
- `InternetService`: Type of internet service subscribed (DSL/Fiber optic/No)
- `OnlineSecurity`: Whether the customer has online security (Yes/No/No internet service)
- `OnlineBackup`: Whether the customer has online backup (Yes/No/No internet service)
- `DeviceProtection`: Whether the customer has device protection (Yes/No/No internet service)
- `TechSupport`: Whether the customer has tech support (Yes/No/No internet service)
- `StreamingTV`: Whether the customer has streaming TV (Yes/No/No internet service)
- `StreamingMovies`: Whether the customer has streaming movies (Yes/No/No internet service)
- `Contract`: Type of contract (Month-to-month/One year/Two year)
- `PaperlessBilling`: Whether the customer has opted for paperless billing (Yes/No)
- `PaymentMethod`: Payment method used by the customer
- `MonthlyCharges`: Monthly charges incurred by the customer
- `TotalCharges`: Total charges incurred by the customer
- `Churn`: Whether the customer churned (Yes/No)

Please refer to the Kaggle dataset page for more detailed information on the dataset.

## Getting Started

These instructions will help you get started with the churn predictor project.

### Prerequisites

Make sure you have the following prerequisites installed:

- Python 3.x
- Jupyter Notebook or any preferred IDE

### Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/metarex21/churn-predicton.git
   ```
