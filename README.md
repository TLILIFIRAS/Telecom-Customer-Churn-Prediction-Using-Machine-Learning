# Telecom Customer Churning Prediction Project



## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Installation](#installation)
- [Dependencies](#dependencies)
- [Dataset](#dataset)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Churn Scenarios](#churn-scenarios)
- [Decision Cycle of a Subscriber](#decision-cycle-of-a-subscriber)
- [Churn Segments](#churn-segments)
- [Model Building](#model-building)
- [Evaluation](#evaluation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Welcome to the Telecom Customer Churning Prediction Project! The primary objective of this project is to predict telecom customer churn using data science techniques. Churn prediction helps telecom companies identify customers at risk of churning, enabling them to implement targeted retention strategies and improve customer satisfaction.

## Project Overview
In this project, we have performed an end-to-end exploratory data analysis (EDA) to gain insights into the dataset and identify customer characteristics that are more likely to lead to churn. Leveraging these insights, we have built predictive models using Python, pandas, matplotlib, seaborn, and scikit-learn to forecast potential churners.

## Installation
To get started with this project, follow these installation steps:

```bash
# Clone the repository
git clone https://github.com/TLILIFIRAS/Telecom-Customer-Churn-Prediction-Using-Machine-Learning.git
cd telecom-churn-prediction
# Install the required Python packages (if not done already)
pip install pandas matplotlib seaborn scikit-learn
```
# Dependencies
Ensure you have the following Python packages installed to run this project:

- Python 3.7+
- pandas 1.3.3
- matplotlib 3.4.3
- seaborn 0.11.2
- scikit-learn 0.24.2

## Dataset
The dataset used in this project contains information about telecom customers, including their usage patterns, billing details, and service engagement. It also includes a binary target variable indicating whether a customer has churned or not. We have explored the data to understand its structure and distribution.

## Exploratory Data Analysis
We have conducted extensive exploratory data analysis (EDA) to gain valuable insights into the dataset. The Jupyter Notebook `Exploratory Data Analysis.ipynb` presents visualizations and data summaries that helped us understand the patterns and characteristics of churners and non-churners.

## Churn Scenarios
In this project, we have considered different churn scenarios that customers might experience:

1. Voluntary Churn: Customers actively decide to switch to a competitor or cancel their subscription due to various reasons.
2. Involuntary Churn: Customers are forced to leave due to reasons beyond their control, such as relocation to an area without service coverage.
3. Reactive Churn: Customers decide to leave because the company fails to address their issues or complaints effectively.
4. Proactive Churn: The company identifies potential churners through predictive analytics and takes proactive measures to retain them.

## Decision Cycle of a Subscriber
The decision cycle of a subscriber involves several stages leading up to the decision to churn or remain with the current telecom provider:

1. Service Usage Period: The subscriber uses the telecom services during this period, forming their overall experience.
2. Dissatisfaction or Trigger Event: A triggering event or dissatisfaction with the service prompts the subscriber to consider alternatives.
3. Consideration Phase: The subscriber evaluates other telecom service providers or plans as potential replacements.
4. Decision to Churn: After considering options, the subscriber decides to either stay with the current provider or switch to another one.
5. Churn or Retention: The subscriber either churns and switches to another provider or remains with the current provider based on their decision.

## Churn Segments
We have identified different churn segments to group customers based on their characteristics and likelihood of churn. This segmentation allows us to tailor retention strategies for specific groups. Some common churn segments include:

- High-Value Churners: Customers who spend a lot on telecom services but are at high risk of churning.
- Low-Engagement Churners: Customers who use minimal services and are at risk of churning due to low engagement.
- Contract-End Churners: Customers whose contracts are nearing expiration, making them more likely to churn.
- Competitor-Attracted Churners: Customers actively considering offers from competitors and are susceptible to churn.
- Discount-Dependent Churners: Customers highly sensitive to discounts and likely to churn if not offered competitive pricing.
- Unhappy Customer Churners: Customers expressing dissatisfaction with the service and at risk of churn.
- Inactive Churners: Customers who have been inactive for an extended period and are likely to churn.

## Model Building
We have created predictive models to forecast customer churn. Refer to the Jupyter Notebook `Machine Learning Modeling.ipynb` to explore the model building process. We have employed scikit-learn to train and evaluate the models.

## Evaluation
The models have been evaluated using appropriate metrics to measure their performance in predicting churn. The results and discussions are available in the `Machine Learning Modeling.ipynb` notebook.

## Usage
For replicating the project, follow the installation steps provided above. Then, explore the Jupyter Notebooks for EDA and model building to understand the project's workflow. You can also use the trained model for predicting customer churn in your dataset.

## Contributing
We welcome contributions to this project. If you have ideas or suggestions for improvement, feel free to fork the repository, make changes, and submit a pull request.

## License
This project is released under the MIT License. You are free to use and modify the code while attributing the original work to us.

