# PRODIGY_DS_03
Prodigy InfoTech Internship: Data Analysis Insights

# Decision Tree Classifier for Customer Purchase Prediction

## Project Overview

This project focuses on developing a **Decision Tree Classifier** to forecast whether a customer will buy a product or service, utilizing demographic and behavioral data. The dataset is derived from the **Bank Marketing Dataset** available in the UCI Machine Learning Repository. This work is part of Task 3 of my internship at Prodigy InfoTech.

The original link of dataset: https://archive.ics.uci.edu/dataset/222/bank+marketing

### Key Features:
- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Extraction (Engineering)
- Building and Tuning a Decision Tree Classifier
- Model Evaluation with various metrics such as:
  - accuracy
  - precision
  - recall
  - F1-score
  - ROC-AUC

## Dataset

The dataset consists of customer information, including demographic and behavioral data such as:
- **Age**: The age of the customer.
- **Job**: The customer's job type.
- **Marital Status**: The marital status of the customer.
- **Education**: The level of education.
- **Default**: Whether the customer has credit in default.
- **Balance**: The customer's balance in their account.
- **Housing Loan**: Whether the customer has a housing loan.
- **Personal Loan**: Whether the customer has a personal loan.
- **Contact Communication**: Details regarding the communication type and duration.
- **Outcome**: Whether the customer purchased the product (target variable).

## Project Workflow

### 1. Data Preprocessing
- **Handling Missing Values**: Identify and deal with missing values.
- **Encoding Categorical Features**: Categorical features are encoded into numerical values using techniques like one-hot encoding.
- **Feature Scaling**: Continuous features such as "Balance" and "Age" are scaled for consistency.

### 2. Exploratory Data Analysis (EDA)
- **Data Distribution**: Visualizations of key features using histograms, bar charts, and box plots.
- **Correlation Analysis**: Heatmaps to showcase correlations between features and the target variable.
- **Class Imbalance**: Analysis of the balance between classes (purchase vs. no purchase).

### 3. Decision Tree Classifier
- **Model Training**: A decision tree model is built using the **scikit-learn** library.
- **Hyperparameter Tuning**: Optimization techniques like Grid Search are applied to fine-tune parameters like `max_depth`, `min_samples_split`, and `min_samples_leaf`.
  
### 4. Model Evaluation
- **Confusion Matrix**: Visualize true positives, false positives, true negatives, and false negatives.
- **Classification Report**: Includes precision, recall, F1-score, and support for both classes.
- **ROC-AUC Curve**: Evaluate the trade-off between true positive rate and false positive rate.

## Contact Information

For any inquiries or collaborations, feel free to reach out:

- Email: [raz0208@gmail.com](mailto:raz0208@gmail.com)
- LinkedIn: [Reza Azari Aghouieh](https://www.linkedin.com/in/reza-azari-aghoueh/)
