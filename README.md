# 🚢 Titanic Dataset — Exploratory Data Analysis

This project focuses on performing **Exploratory Data Analysis (EDA)** on the famous **Titanic dataset** to understand the factors associated with passenger survival.

## 📌 Project Overview

The Titanic dataset contains information about passengers such as their age, gender, passenger class, fare, and survival status.

The main objective of this project is to explore the dataset, identify patterns, and extract meaningful insights through data analysis and visualization.

## 🎯 Objectives

- Understand the structure of the dataset
- Perform data cleaning and preprocessing
- Analyze missing values
- Explore numerical and categorical variables
- Study relationships between passenger characteristics and survival
- Create meaningful visualizations
- Extract insights from the data

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📂 Dataset

The dataset contains information about Titanic passengers.

### Important Features

| Feature | Description |
|---|---|
| `PassengerId` | Unique passenger ID |
| `Survived` | Survival status (0 = No, 1 = Yes) |
| `Pclass` | Passenger class |
| `Name` | Passenger name |
| `Sex` | Passenger gender |
| `Age` | Passenger age |
| `SibSp` | Number of siblings/spouses aboard |
| `Parch` | Number of parents/children aboard |
| `Ticket` | Ticket number |
| `Fare` | Passenger fare |
| `Cabin` | Cabin information |
| `Embarked` | Port of embarkation |

## 🔍 EDA Performed

### 1. Data Understanding

- Checked dataset shape
- Examined data types
- Generated descriptive statistics
- Analyzed numerical and categorical variables

### 2. Data Cleaning

- Checked for missing values
- Analyzed missing-value patterns
- Handled missing values where required
- Checked for duplicate records

### 3. Univariate Analysis

Explored individual variables using:

- Histograms
- Count plots
- Box plots
- Distribution plots

### 4. Bivariate & Multivariate Analysis

Analyzed relationships between:

- `Sex` and `Survived`
- `Pclass` and `Survived`
- `Age` and `Survived`
- `Fare` and `Survived`
- `Embarked` and `Survived`
- `Pclass`, `Sex` and `Survived`

## 📊 Key Insights

Some important patterns observed during the analysis:

- Survival rates varied across different passenger classes.
- Gender showed a strong relationship with survival.
- Age distributions differed between survivors and non-survivors.
- Passenger fare showed noticeable differences between survival groups.
- Combining multiple features provided deeper insights into survival patterns.

> These observations describe patterns in the dataset and should not be interpreted as causal relationships.

## 📁 Project Structure

```text
Titanic-EDA/
│
├── Titanic_EDA.ipynb
├── train.csv
└── README.md
