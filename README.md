
# Real-Time Fraud Detection System for Financial Transactions

## Description
This project aims to design and implement a real-time fraud detection system using synthetic mobile money transaction data. The dataset is derived from the PaySim simulator, which reflects real-world financial activities and integrates fraudulent behaviors for research purposes. The primary goal is to enhance fraud detection accuracy, minimize losses, and strengthen user trust through advanced machine learning techniques.

## Dataset Information
The dataset used in this project is a synthetic representation of mobile money transactions. It encompasses a variety of transaction types, including CASH-IN, CASH-OUT, DEBIT, PAYMENT, and TRANSFER, over a simulated period of 30 days. This dataset provides a comprehensive environment for evaluating fraud detection methodologies while addressing the intrinsic privacy concerns associated with financial transactions.

### Key Features:
- **step**: Represents time in hours (1 step = 1 hour).
- **type**: Transaction types (CASH-IN, CASH-OUT, DEBIT, PAYMENT, TRANSFER).
- **amount**: The transaction amount in the local currency.
- **nameOrig**: The customer initiating the transaction.
- **nameDest**: The transaction's recipient customer.
- **isFraud**: Indicates whether the transaction is fraudulent.
- **isFlaggedFraud**: Flags large-scale unauthorized transfers.

**Important Note**: Transactions identified as fraudulent have been annulled, and the columns `oldbalanceOrg`, `newbalanceOrig`, `oldbalanceDest`, and `newbalanceDest` should not be utilized for fraud analysis.

## Installation
To run this project, clone the repository and install the required libraries:

git clone https://github.com/yourusername/fraud_detection_project.git
cd fraud_detection_project
pip install -r requirements.txt


## Usage
1. Open the Jupyter Notebook file (`fraud_detection_notebook.ipynb`) in your preferred environment (e.g., Jupyter Notebook, Jupyter Lab, or VS Code).
2. Execute the cells sequentially to run the analysis and model training.
3. Review the results and visualizations provided in the notebook.

## Model Evaluation
The project utilizes XGBoost for classification tasks and implements techniques such as SMOTE for handling class imbalance, ensuring robust performance in detecting fraudulent transactions.

## Contributing
Contributions are welcome! If you have suggestions for improvements or enhancements, feel free to fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments
- Thanks to the creators of the PaySim simulator for providing a valuable dataset for research.
- Special thanks to the contributors of the libraries used in this project.

## Contact
For any inquiries or feedback, please contact me.
```
