# Natural Language Processing with Disaster Tweets

This repository is part of a project for the 6th moudule of master's studies at the European Leadership University
Student Name: Loai Siwas

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This repository contains code for the "Natural Language Processing with Disaster Tweets" Kaggle competition. The goal of the competition is to predict whether a given tweet is about a real disaster or not. The project uses various natural language processing techniques and machine learning models to classify tweets into the target classes.

## Dataset
The dataset used in this project can be obtained from the Kaggle competition page [here](https://www.kaggle.com/c/nlp-getting-started/overview). The dataset contains the following columns:
- `id`: Unique identifier for each tweet
- `keyword`: A keyword from the tweet (optional)
- `location`: The location from where the tweet was sent (optional)
- `text`: The text content of the tweet
- `target`: The target class (0 for not a disaster, 1 for a real disaster)

## Installation
1. Clone the repository:
`git clone https://github.com/your_username/nlp-disaster-tweets.git`
`cd nlp-disaster-tweets`

2. Install the required dependencies (you may use a virtual environment):
`pip install -r requirements.txt`

## Usage
1. Data Preprocessing: Preprocess the data to handle missing values, clean the text, and perform tokenization as needed.
2. Feature Engineering: Generate features such as Bag of Words or TF-IDF vectors for the text data.
3. Model Training: Train your chosen machine learning or deep learning models on the preprocessed data.
4. Evaluation: Evaluate the model performance using appropriate metrics on a validation set.
5. Prediction: Make predictions on the test data and submit your results to Kaggle.

## Models
The project uses several machine learning models and deep learning architectures for tweet classification. Some of the models explored in this project include:
- Logistic Regression
- MultinomialNB
- SVC

## Evaluation
The performance of the models is evaluated using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC on a validation set. Cross-validation is employed to ensure the model's robustness.

## Results
The best-performing model and its results on the test set are submitted to the Kaggle competition.

## Contributing
Contributions are welcome! If you have any improvements, bug fixes, or new features to add, please open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
