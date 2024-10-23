

---

# Credit Card Fraud Detection Model

## Overview

The **Credit Card Fraud Detection Model** is a machine learning application designed to identify fraudulent transactions in credit card data using logistic regression. The model utilizes a balanced dataset containing both legitimate and fraudulent transactions to effectively predict whether a given transaction is likely to be fraudulent or legitimate.

## Features

- **Data Preprocessing**: The model handles imbalanced datasets by undersampling legitimate transactions to match the number of fraudulent transactions, ensuring a balanced training dataset.
- **Model Training**: Utilizes logistic regression to classify transactions based on 30 input features derived from transaction data.
- **Streamlit Interface**: Provides an interactive web application for users to input transaction features and receive real-time predictions about the legitimacy of the transaction.
- **User Input**: Users can input transaction features in a comma-separated format, along with the expected class label (0 for legitimate, 1 for fraudulent).

## Technologies Used

- Python
- Scikit-learn (for machine learning)
- Pandas (for data manipulation)
- NumPy (for numerical computations)
- Streamlit (for creating the web application)

## Dataset

The model uses the [Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data) available on Kaggle. This dataset contains transactions made by credit cards in September 2013 by European cardholders, with 492 fraudulent transactions out of a total of 284,807.

## Getting Started

### Prerequisites

- Python 3.x
- Required libraries: `pandas`, `numpy`, `scikit-learn`, `streamlit`
  
### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/FraudDetection.git
   cd FraudDetection
   ```

2. Install the required packages:
   ```bash
   pip install pandas numpy scikit-learn streamlit
   ```

3. Download the credit card dataset from Kaggle, and place the `creditcard.csv` file in the project directory.

### Running the Application

To run the Streamlit application, use the following command:
```bash
streamlit run app.py
```

Then, open your browser and go to `http://localhost:8501` to interact with the app.

## Usage

1. Input the transaction features in the specified format.
2. Provide the expected class label (0 for legitimate, 1 for fraudulent).
3. Click "Submit" to receive the model's prediction regarding the transaction's legitimacy.

## Conclusion

This model aims to assist financial institutions in detecting fraudulent transactions and minimizing financial losses. The implementation demonstrates the application of machine learning techniques in real-world scenarios, particularly in finance and risk management.

---

