**Name:** S.DHARANIPRASATH

**Company:** CODTECH IT SOLUTIONS

**ID:** CT08DS5789

**Domain:** MACHINE LEARNING

**Duration:** AUG TO SEPT 2024

**Mentor Name:** MUZAMMIL AHMED


# Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using a machine learning model. The dataset used is highly imbalanced, with a small percentage of transactions being fraudulent. To address this, we employed under-sampling to balance the dataset before training a logistic regression model.

## Table of Contents
- [Dataset](#dataset)
- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Dataset
The dataset used in this project is the [Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud) from Kaggle. It contains transactions made by European cardholders in September 2013. The dataset has 284,807 transactions, out of which 492 are fraudulent (about 0.17%).

- **Features:** 30 numeric features including 'Time', 'Amount', and 28 anonymized features (V1 to V28)
- **Target Variable:** 'Class' (0 for normal transactions, 1 for fraudulent transactions)

## Project Overview
The goal of this project is to build a model that can accurately identify fraudulent transactions. The key steps involved are:
1. Loading and exploring the dataset.
2. Handling the class imbalance using under-sampling.
3. Building and evaluating a logistic regression model.
4. Analyzing the results.

### Key Concepts
- **Under-Sampling:** This technique involves balancing the dataset by reducing the number of normal transactions to match the number of fraudulent ones.
- **Logistic Regression:** A statistical model used for binary classification problems, such as fraud detection.

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Credit_Card_Fraud_Detection.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Credit_Card_Fraud_Detection
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Ensure you have the dataset (`credit_data.csv`) in the root directory.
2. Run the `fraud_detection.py` script to train the model and make predictions:
    ```bash
    python fraud_detection.py
    ```
3. The script will output the accuracy score and other evaluation metrics.

## Results
- The logistic regression model was trained on the balanced dataset.
- The model achieved an accuracy of **X%** on the test data.
- Detailed evaluation metrics and a confusion matrix are provided in the results section of the script.

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

## Output
![WhatsApp Image 2024-08-30 at 20 11 06_d0d920bd](https://github.com/user-attachments/assets/74fc49e1-1198-4448-8009-e2376b9bb608)

