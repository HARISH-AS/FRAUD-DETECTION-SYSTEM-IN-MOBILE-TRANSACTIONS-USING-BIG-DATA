# PySpark Fraud Detection

## Overview
This project implements a fraud detection system using PySpark. It utilizes big data processing techniques to identify fraudulent transactions based on various features extracted from financial datasets.

## Features
- Data preprocessing using PySpark
- Feature engineering for fraud detection
- Model training and evaluation
- Ensemble learning methods for improved accuracy

## Installation
### Prerequisites
Ensure you have the following installed:
- Python (>= 3.7)
- Apache Spark (>= 3.0)
- Jupyter Notebook (optional for running the notebook)

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/pyspark-fraud-detection.git
   cd pyspark-fraud-detection
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook pyspark_fraud_detection.ipynb
   ```

## Usage
1. Load the dataset into PySpark DataFrame.
2. Perform data preprocessing (handling missing values, feature engineering).
3. Train machine learning models using PySpark MLlib.
4. Evaluate model performance using accuracy, precision, recall, and F1-score.
5. Identify fraudulent transactions and analyze feature importance.

## Dataset
The dataset used for fraud detection should contain:
- Transaction ID
- User details (anonymized)
- Transaction amount
- Timestamp
- Fraud label (0 for genuine, 1 for fraudulent)

## Model Details
The project employs an ensemble of models, including:
- Random Forest
- XGBoost
- Logistic Regression
- Meta-classifier for final prediction

## Results & Performance
- The models are evaluated using multiple metrics to ensure high fraud detection accuracy.
- Feature importance analysis helps in understanding key fraud indicators.

## Contributions
Feel free to contribute by submitting pull requests or raising issues.

## License
This project is licensed under the MIT License.

