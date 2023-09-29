### Credit-Card-Fraud-Detection-ML
### Credit card fraud detection project using machine learning. Utilizing Kaggle data and Python with Scikit-learn, we apply LOF and Isolation Forest algorithms, aiming for high precision and recall to aid financial institutions and customers in fraud prevention.

### Title: Credit Card Fraud Detection with Machine Learning 🕵️‍♂️🔍💳🛡️

Description: This GitHub repository hosts a project dedicated to combating credit card fraud using machine learning techniques. Credit card fraud is a pervasive issue, often eluding detection within a sea of legitimate transactions. To tackle this challenge, we leverage the Kaggle dataset and employ two robust anomaly detection algorithms: Local Outlier Factor (LOF) and Isolation Forest.

Our implementation is powered by Python 🐍 and the Scikit-learn library 📊. We kickstart the process by preprocessing the data, tackling duplicates, and handling missing values. Next, we unleash the power of LOF and Isolation Forest to unearth anomalies hidden in the dataset 📈🕵️‍♂️. Performance evaluation is a key component, with metrics like precision, recall, F1-score, and ROC curve analysis playing pivotal roles 📉📋.

Our ultimate aim is to craft a highly effective model that excels in both precision and recall when it comes to detecting credit card fraud. By achieving this goal, our project stands to benefit financial institutions and customers alike, providing them with a powerful tool to promptly identify fraudulent transactions and take the necessary actions to prevent further financial losses. Join us in the fight against credit card fraud by exploring this repository and contributing to our mission! 💼🚀💰



### Code Explanation

1. **Import Libraries**: The script begins by importing essential libraries such as NumPy, Seaborn, Matplotlib, and Pandas for data manipulation, visualization, and analysis.

2. **Load Dataset**: It loads a credit card transaction dataset from a CSV file and prints the column names.

3. **Data Exploration**: This section provides an overview of the dataset by printing its shape, summary statistics, and displaying the first few rows. It also checks for missing values.

4. **Plot Histograms**: Histograms of the dataset are plotted for each column to visualize data distribution.

5. **Segregate Data**: Valid and fraudulent transactions are separated into two DataFrames, 'Valid' and 'Fraud.'

6. **Calculate Outlier Fraction**: The code calculates the outlier fraction as the ratio of fraudulent transactions to valid transactions.

7. **Print Transaction Counts**: It prints the counts of fraud and valid transactions in the dataset.

8. **Describe Amount for Fraud and Valid Transactions**: Summary statistics for the 'Amount' column are provided separately for fraud and valid transactions.

9. **Correlation Matrix**: The code computes and visualizes the correlation matrix of the dataset using a heatmap.

10. **Data Preparation**: Features and target variable are prepared for modeling, and 'Class' is removed from the feature list.

11. **Import Libraries for Model Evaluation**: Libraries for model evaluation, such as `classification_report` and `accuracy_score`, are imported. Two anomaly detection algorithms are also imported.

12. **Define Model Parameters and Classifiers**: The script sets parameters for model consistency and defines two classifiers, Isolation Forest and Local Outlier Factor.

13. **Model Evaluation**: The code iterates through the classifiers, fits the models, computes predictions, and evaluates their performance in detecting fraud. It prints error counts, accuracy scores, and classification reports for each classifier.

### Usage

To use this code in your project, follow these steps:
1. Ensure you have the required libraries installed (NumPy, Seaborn, Matplotlib, Pandas, scikit-learn).
2. Provide your credit card transaction dataset as a CSV file.
3. Customize the script for your dataset if needed.
4. Run the script to perform fraud detection using Isolation Forest and Local Outlier Factor.
5. Analyze the results and adjust the models as necessary for your specific use case.

### Dependencies

- NumPy
- Seaborn
- Matplotlib
- Pandas
- scikit-learn
