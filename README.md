# Online Payment Fraud Detection using Machine Learning

## Description
This project compares three different classification models for detecting online payment fraud. It aims to identify the most effective model for distinguishing fraudulent transactions from legitimate ones. This project is intended for data scientists, machine learning enthusiasts, and financial institutions looking to enhance fraud detection mechanisms.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Project Overview](#project-overview)
- [Contributing](#contributing)
- [License](#license)

## Installation
To set up this project on your local machine, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-name/online-payment-fraud.git
   ```
2. Navigate to the project directory:
   ```bash
   cd online-payment-fraud
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Ensure Jupyter Notebook is installed:
   ```bash
   pip install notebook
   ```
5. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Usage
1. Open the Jupyter Notebook file (`3classification-model-compare-online-payment-fraud.ipynb`).
2. Run the notebook cells in sequence to:
   - Load and preprocess the dataset.
   - Train and evaluate three different classification models.
   - Compare model performances using key evaluation metrics.
3. Analyze the results and insights generated.

## Project Overview
This project compares the following three classification models:
- **Logistic Regression**
- **Random Forest Classifier**
- **XGBoost Classifier**

The models are trained on an online payment transaction dataset. The primary goal is to determine which model performs best in terms of accuracy, precision, recall, and F1-score.

### Key Features:
- **Preprocessing Steps:** Data cleaning, handling missing values, feature engineering.
- **Model Training:** Hyperparameter tuning for optimal results.
- **Evaluation Metrics:** ROC-AUC, confusion matrix, precision-recall curves.
- **Comparison & Insights:** Discussion on model strengths and weaknesses.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to your branch (`git push origin feature-branch`).
5. Create a Pull Request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

