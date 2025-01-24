Exploratory Data Analysis (EDA) on Bank Churn Dataset

This Jupyter Notebook contains an exploratory data analysis (EDA) on a dataset related to bank customer churn. The dataset includes various customer attributes such as credit score, geography, gender, age, tenure, balance, number of products, and whether the customer has exited the bank.

 Dataset Overview

The dataset used in this analysis is named `Bank_Churn.csv`. It contains 10,000 entries with 13 columns, including:

- CustomerId: Unique identifier for each customer.
- Surname: Customer's surname.
- CreditScore: Customer's credit score.
- Geography: Customer's location (e.g., France, Spain).
- Gender: Customer's gender.
- Age: Customer's age.
- Tenure: Number of years the customer has been with the bank.
- Balance: Customer's account balance.
- NumOfProducts: Number of bank products the customer uses.
- HasCrCard: Whether the customer has a credit card (1 for yes, 0 for no).
- IsActiveMember: Whether the customer is an active member (1 for yes, 0 for no).
- EstimatedSalary: Customer's estimated salary.
- Exited: Whether the customer has exited the bank (1 for yes, 0 for no).

 Analysis Steps

1. Data Loading: The dataset is loaded using the `pandas` library.
2. Initial Inspection: The first few rows of the dataset are displayed to get an initial understanding of the data.
3. Missing Values: The dataset is checked for missing values. It is found that there are no missing values.
4. Duplicates: The dataset is checked for duplicate entries. No duplicates are found.
5. Column Names: The column names are displayed to understand the structure of the dataset.
6. Data Types: The data types of each column are inspected using the `info()` method.
7. Basic Statistics: Basic statistical summaries of the dataset are generated using the `describe()` method.
8. Data Visualization: Various visualizations are created using `matplotlib` and `seaborn` to explore the relationships between different variables and to identify patterns or trends.

 Key Findings

- No Missing Values: The dataset is clean with no missing values.
- No Duplicates: There are no duplicate entries in the dataset.
- Data Types: The dataset contains a mix of integer, float, and object (string) data types.
- Customer Demographics: The dataset includes customers from different geographies, with varying ages, credit scores, and account balances.
- Churn Rate: The target variable `Exited` indicates whether a customer has left the bank. The churn rate can be calculated and visualized to understand the proportion of customers who have exited.

 Visualizations

- Histograms: Histograms are plotted for numerical columns like `CreditScore`, `Age`, `Balance`, and `EstimatedSalary` to understand their distributions.
- Bar Plots: Bar plots are used to visualize the distribution of categorical variables like `Geography`, `Gender`, and `NumOfProducts`.
- Correlation Matrix: A correlation matrix is created to explore the relationships between numerical variables.
- Churn Analysis: The relationship between churn and other variables (e.g., `CreditScore`, `Age`, `Balance`) is explored using various plots.

 Dependencies

The following Python libraries are used in this analysis:

- pandas: For data manipulation and analysis.
- numpy: For numerical operations.
- matplotlib: For creating static, animated, and interactive visualizations.
- seaborn: For statistical data visualization.

 How to Run

1. Ensure you have the required libraries installed. You can install them using pip:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
2. Download the `Bank_Churn.csv` dataset and place it in the same directory as the notebook.
3. Open the Jupyter Notebook and run each cell sequentially to perform the analysis.

 Conclusion

This exploratory data analysis provides a comprehensive overview of the bank customer churn dataset. By understanding the data's structure, distributions, and relationships, we can gain insights that may help in predicting customer churn and developing strategies to retain customers.
