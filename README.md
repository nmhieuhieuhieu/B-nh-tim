# Heart Disease Prediction

This repository contains a project aimed at predicting heart disease using various machine learning algorithms, including Logistic Regression (LR), Random Forest (RF), AdaBoost, and Gaussian Naive Bayes. Additionally, it includes a Flask web application for making predictions based on user inputs.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)
- [Dataset](#dataset)
- [Results](#results)
- [Flask Web Application](#flask-web-application)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The goal of this project is to develop models that can predict the likelihood of heart disease based on various health indicators. The models help in early detection and intervention, potentially saving lives.

## Features

- Data preprocessing and cleaning
- Implementation of Logistic Regression, Random Forest, AdaBoost, and Gaussian Naive Bayes models
- Evaluation and comparison of model performance
- Flask web application for real-time prediction

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/heart-disease-prediction.git
    cd heart-disease-prediction
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```sh
    python -m venv venv
    source venv/bin/activate # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Preprocess the data:
    ```sh
    python preprocess.py
    ```

2. Train the models:
    - Logistic Regression:
      ```sh
      python train_lr.py
      ```

    - Random Forest:
      ```sh
      python train_rf.py
      ```

    - AdaBoost:
      ```sh
      python train_adaboost.py
      ```

    - Gaussian Naive Bayes:
      ```sh
      python train_gaussian.py
      ```

3. Evaluate the models:
    ```sh
    python evaluate.py
    ```

## Models

- **Logistic Regression (LR)**: A simple yet effective machine learning algorithm for binary classification.
- **Random Forest (RF)**: An ensemble learning method that constructs multiple decision trees for improved accuracy.
- **AdaBoost**: An ensemble learning method that combines weak classifiers to create a strong classifier.
- **Gaussian Naive Bayes**: A probabilistic classifier based on Bayes' theorem with strong independence assumptions.

## Dataset

The dataset used in this project consists of health indicators relevant to heart disease prediction. The data is preprocessed and cleaned before being used for model training. The dataset should be placed in the `data` directory. A sample dataset can be found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/heart+disease).

## Results

The performance of each model is evaluated using metrics such as accuracy, precision, recall, and F1-score. Detailed results and comparisons are provided in the `results` directory.

## Flask Web Application

A simple Flask web application is provided to make real-time heart disease predictions based on user inputs.

1. Run the Flask app:
    ```sh
    python app.py
    ```

2. Open your web browser and go to `http://127.0.0.1:5000/` to access the application.

The web application allows users to input various health indicators and get predictions on the likelihood of heart disease.

## Contributing

We welcome contributions to this project. Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Create a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
