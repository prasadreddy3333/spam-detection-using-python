# Spam Email Detector

Spam Email Detector is a Python project aimed at automatically classifying emails as either spam or non-spam (ham) using machine learning techniques. The project includes data preprocessing, exploratory data analysis, model training, and evaluation.

## Overview

Spam emails, also known as junk mail, pose a significant threat to users by flooding their inbox with unwanted messages, potentially containing scams or phishing attempts. This project addresses this issue by implementing a machine learning model to automatically detect and classify spam emails.

## Key Features

- Data preprocessing: The project involves cleaning and preprocessing email data to prepare it for analysis and model training.
- Exploratory Data Analysis (EDA): Utilizing various visualization techniques to gain insights into the dataset, including the distribution of spam and non-spam emails, message lengths, and correlations between features.
- Model Training: Training a logistic regression model using the preprocessed data to classify emails as spam or non-spam.
- Evaluation Metrics: Assessing the model's performance using accuracy, precision, recall, and F1-score metrics.
- Custom Word Prediction: Demonstrating the model's capability to predict the category (spam or non-spam) of custom words or short phrases.

## Setup

To set up the project locally, follow these steps:

1. Clone the repository:

    `https://github.com/MehmoodSheikh/SPAM-EMAIL-DETECTION.git`

2. Install the required dependencies:

    `https://github.com/MehmoodSheikh/SPAM-EMAIL-DETECTION/blob/main/requirement.txt`

3. Run the project:

   `https://github.com/MehmoodSheikh/SPAM-EMAIL-DETECTION/blob/main/Email%20Spam%20Detection.ipynb`


## Dataset

The project utilizes the "spam.csv" dataset containing email messages labeled as spam or non-spam. The dataset includes two columns: "Category" (spam or ham) and "Message" (email content).

## Usage

The main script, `Email Spam Detection.ipynb`, encompasses the entire workflow of the project, including data preprocessing, model training, and evaluation. Users can modify the script or integrate it into their applications for automated email classification.

## Results

The trained logistic regression model achieves an accuracy of 0.98 on the test set, demonstrating its effectiveness in classifying spam emails.

## License

This project is licensed under the [MIT License](LICENSE).

