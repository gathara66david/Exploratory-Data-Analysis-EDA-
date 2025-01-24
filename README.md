 Explanatory Data Analysis (EDA) on Bank Churn Dataset

This Jupyter notebook performs an exploratory data analysis (EDA) on a bank churn dataset. The dataset contains information about customers of a bank, including whether they have exited (churned) or not. The goal of this analysis is to understand the factors that contribute to customer churn and to prepare the data for further modeling.

 Dataset Overview

The dataset contains the following columns:

- CustomerId: Unique identifier for each customer.
- Surname: Customer's surname.
- CreditScore: Credit score of the customer.
- Geography: Country of the customer.
- Gender: Gender of the customer.
- Age: Age of the customer.
- Tenure: Number of years the customer has been with the bank.
- Balance: Account balance of the customer.
- NumOfProducts: Number of bank products the customer uses.
- HasCrCard: Whether the customer has a credit card (1) or not (0).
- IsActiveMember: Whether the customer is an active member (1) or not (0).
- EstimatedSalary: Estimated salary of the customer.
- Exited: Whether the customer has exited (1) or not (0).

 Steps Performed in the Notebook

1. Importing Libraries: The necessary libraries such as pandas, numpy, matplotlib, and seaborn are imported.
2. Loading the Dataset: The dataset is loaded from a CSV file.
3. Initial Data Inspection: The first few rows of the dataset are displayed to get an initial understanding of the data.
4. Checking for Missing Values: The dataset is checked for any missing values.
5. Checking for Duplicates: The dataset is checked for duplicate entries.
6. Data Types and Summary: The data types of the columns and a summary of the dataset are displayed.
7. Churn Rate Calculation: The churn rate (percentage of customers who have exited) is calculated and visualized.
8. Feature Engineering: New features such as `BalanceToSalaryRatio`, `AgeGroup`, and `TenureGroup` are created to enhance the dataset.
9. Outlier Detection: A box plot is used to detect outliers in the `CreditScore` column.
10. Visualizations: Various visualizations are created to understand the distribution of different features and their relationship with churn.

 Key Findings

- Churn Rate: The churn rate is approximately 20.37%.
- No Missing Values: The dataset has no missing values.
- No Duplicates: The dataset contains no duplicate entries.
- Feature Engineering: New features like `BalanceToSalaryRatio`, `AgeGroup`, and `TenureGroup` were created to provide more insights into the data.
- Outliers: The `CreditScore` column has some outliers, which may need to be addressed in further analysis.

 Visualizations

- Churn Distribution: A count plot shows the distribution of churned vs. non-churned customers.
- Box Plot for CreditScore: A box plot is used to detect outliers in the `CreditScore` column.

 Next Steps

- Further Feature Engineering: Additional features could be created to capture more insights.
- Modeling: The dataset can be used to build predictive models to identify customers at risk of churning.
- Handling Outliers: Outliers in the `CreditScore` column should be addressed to improve model performance.

 Dependencies

- pandas
- numpy
- matplotlib
- seaborn

 How to Run

1. Ensure you have the required libraries installed.
2. Download the dataset and update the file path in the notebook.
3. Run the notebook cells sequentially to perform the analysis.

 Author

David Gathara Marigi

 License

This project is licensed under the MIT License. See the LICENSE file for details.
