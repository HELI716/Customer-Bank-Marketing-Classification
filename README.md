# Customer Bank Marketing Classification

## Project Overview
This project utilizes machine learning techniques to classify whether bank customers will subscribe to a term deposit based on an analysis of marketing campaigns. The approach involves preprocessing the dataset, training a classification model, and evaluating its performance to ensure the model's efficacy in predicting customer responses.

## Background
Financial institutions routinely use targeted marketing campaigns to promote new products. The success of these campaigns depends heavily on identifying the right customers. This project applies data science methodologies to improve targeting strategies and increase conversion rates.

## Dataset
The dataset includes details from direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe to a term deposit.

### Features
- **Age:** Age of the client.
- **Job:** Type of job.
- **Marital:** Marital status.
- **Education:** Education level.
- **Default:** Has credit in default?
- **Housing:** Has housing loan?
- **Loan:** Has personal loan?
- **Contact:** Contact communication type.
- **Month:** Last contact month of year.
- **Day_of_week:** Last contact day of the week.
- **Duration:** Last contact duration, in seconds.

### Target
- **Deposit:** Has the client subscribed to a term deposit? (binary: "yes","no")

## Prerequisites
- Python 3.8+
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Installation
Clone this repository and install the required packages:
```
git clone https://github.com/your-username/repository-name.git
cd repository-name
pip install -r requirements.txt
```

## Usage
Navigate to the cloned repository and launch Jupyter Notebook to open the `Customer_Bank_Marketing_Classification.ipynb` file:
```
jupyter notebook Customer_Bank_Marketing_Classification.ipynb
```
Execute the notebook cells sequentially to observe the analysis and results.

## Model
The model is built using Scikit-learn's classification algorithms. It includes steps for data cleaning, feature engineering, model selection, and hyperparameter tuning. The performance metrics used to evaluate the model are accuracy, precision, recall, and F1-score.
