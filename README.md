### 1. Dataset Explanation

The dataset used for credit score prediction contains various attributes related to individuals' financial and personal information. Here's an explanation of the key columns:

- **ID**: Unique identifier for each record
- **Customer_ID**: Unique identifier for each customer
- **Month**: Month of the year
- **Name**: Name of the person
- **Age**: Age of the person
- **SSN**: Social Security Number of the person
- **Occupation**: Occupation of the person
- **Annual_Income**: Annual income of the person
- **Monthly_Inhand_Salary**: Monthly in-hand salary of the person
- **Num_Bank_Accounts**: Number of bank accounts of the person
- **Num_Credit_Card**: Number of credit cards the person has
- **Interest_Rate**: Interest rate on the credit card of the person
- **Num_of_Loan**: Number of loans taken by the person from the bank
- **Type_of_Loan**: Types of loans taken by the person from the bank
- **Delay_from_due_date**: Average number of days delayed by the person from the date of payment
- **Num_of_Delayed_Payment**: Number of payments delayed by the person
- **Changed_Credit_Card**: Percentage change in the credit card limit of the person
- **Num_Credit_Inquiries**: Number of credit card inquiries by the person
- **Credit_Mix**: Classification of Credit Mix of the customer
- **Outstanding_Debt**: Outstanding balance of the person
- **Credit_Utilization_Ratio**: Credit utilization ratio of the credit card of the customer
- **Credit_History_Age**: Age of the credit history of the person
- **Payment_of_Min_Amount**: Whether the person paid the minimum amount only
- **Total_EMI_per_month**: Total EMI per month of the person
- **Amount_invested_monthly**: Monthly amount invested by the person
- **Payment_Behaviour**: Payment behavior of the person
- **Monthly_Balance**: Monthly balance left in the account of the person
- **Credit_Score**: Credit score of the person

### 2. Code Explanation

The code provided in the repository includes several steps:

1. **Data Preprocessing**: Data cleaning and transformation tasks are performed, such as handling missing values, encoding categorical variables, and splitting the data into training and testing sets.

2. **Model Training**: A Random Forest Classifier model is trained on the preprocessed data to predict credit scores based on the provided attributes.

3. **Model Evaluation**: The trained model is evaluated using various metrics such as confusion matrix, classification report, and accuracy score to assess its performance.

4. **Handling Class Imbalance**: To handle class imbalance in the dataset, undersampling is performed on the majority classes to balance the distribution of credit scores.
