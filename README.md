Loan Default Prediction Using Machine Learning

This project aims to predict the likelihood of loan default based on customer demographic and financial data. The dataset used consists of structured tabular data and is processed to train and evaluate multiple machine learning models.

📋 Project Structure

Input Data: Structured CSV datasets (loan applications) uploaded to DBRepo with persistent identifiers (PIDs).
Models Trained:
Logistic Regression
Random Forest
XGBoost
Outputs:
Trained machine learning models (.pkl files)
Performance evaluation metrics (.csv file)
Training time comparison plot (.png file)
Confusion matrix for the best model (.png file)
🛠️ Technologies and Libraries

Python 3.10
pandas
scikit-learn 1.3.0
xgboost 1.6.2
matplotlib 3.7.1
joblib
📈 Workflow

Data Loading: Data is retrieved using PID references from DBRepo.
Data Preprocessing:
Label Encoding of target variable
Feature scaling
Model Training and Evaluation:
Train Logistic Regression, Random Forest, and XGBoost models
Calculate evaluation metrics: Accuracy, F1-Score (macro), Precision, Recall
Generate confusion matrices and training time comparisons
Result Saving:
Save trained models
Save evaluation plots and metrics
Upload outputs to TUWRD with assigned PIDs
📂 Output Artifacts (Available via TUWRD)

Logistic Regression Model: https://doi.org/10.70124/7stkt-n6r66
Random Forest Model: https://doi.org/10.70124/310hb-b1b27
XGBoost Model: https://doi.org/10.70124/6caqy-rta71
Training Time Plot: https://doi.org/10.70124/xnkf1-7e276
Confusion Matrix (XGBoost): https://doi.org/10.70124/zx8g1-hn084
Model Performance Metrics Table: https://doi.org/10.70124/1fkmb-p3z93
⚖️ Licensing

Code: Licensed under MIT License.
Data and Models: Shared under CC-BY 4.0 or CC0 1.0 where applicable.
🧠 FAIR Principles

This project follows the FAIR principles (Findable, Accessible, Interoperable, Reusable) by:

Using PID identifiers for datasets and models
Providing rich metadata (FAIR4ML, Croissant, CodeMeta)
Publishing code and documentation openly for reproducibility

