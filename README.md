# Wisabi Bank ATM Transaction Analysis with Power BI

## Project Overview

This data analytics project focuses on analyzing ATM transactions for Wisabi Bank, utilizing Power BI for comprehensive insights. The dataset comprises the Transactions fact table, along with dimension tables including Location, Customers, Transaction Type, Hour, and Calendar. The analysis involves data cleaning, transformation, and visualization.

## Business Questions Explored

1. **Average Transaction Amount by Location and Transaction Type**
   - This analysis identifies the average transaction amount based on location and transaction type, providing key financial insights.

2. **ATM Location with Highest Transaction Frequency**
   - Determining which ATM location experiences the highest transaction volume, and identifying the most active time of day.

3. **Age Group with Highest Transaction Volume**
   - Analyzing the age groups with the highest number of transactions, along with their preferred transaction types.

4. **Trend Analysis of Transaction Volume and Amount**
   - This section provides a temporal perspective on transaction volume and amount, identifying any seasonal trends or patterns.

5. **Most Common Transaction Type**
   - Analyzing the most frequently performed transaction type, and exploring how it varies by location and customer type.

6. **Average Transaction Amount and Frequency by Occupation and Age Group**
   - This analysis delves into transaction behavior by occupation and age group, providing valuable customer distribution of withdrawals, savings, balance enquiries, and transfers, factoring in location and time of day.


7. **Outliers and Distribution of Transaction Amounts**
   - This section explores the distribution of transaction amounts and identifies any outliers.

8. **ATM Utilization Rates**
   - Evaluating which ATM locations have the highest and lowest utilization rates, while examining contributing factors.

9. **Transaction Time Analysis**
    - Identifying the average transaction time based on location, transaction type, time of day, customer type, and occupation.

## Scope

This data analytics project encompasses in-depth analysis of the provided ATM transactions data. It involves thorough data cleaning, transformation, and visualization utilizing Excel and Power BI. The project leverages key tables including Transactions fact, Location dimension, Customers dimension, Transaction Type dimension, Hour dimension, and Calendar dimension.

## Expected Deliverables

The project will yield a set of interactive and user-friendly reports and dashboards. These deliverables aim to empower the Wisabi Bank team with data-driven insights for enhancing customer experience and optimizing operations.

## Dataset Explanation

### Transactions Fact Table
- **TransactionID**: Unique identifier for each transaction in the database.
- **TransactionStartDatetime**: Datetime when the transaction started.
- **TransactionEndDatetime**: Datetime when the transaction was completed.
- **Cardholder ID**: Unique identifier for the cardholder performing the transaction.
- **Location ID**: Unique identifier for the location of the ATM where the transaction occurred.
- **Transaction Type ID**: Unique identifier for the type of transaction that was performed (e.g., withdrawal, savings, balance enquiry, transfer).
- **Transaction Amount**: Amount of money involved in the transaction.

### Location Dimension Table
- **Location ID**: Unique identifier for the ATM location.
- **Location Name**: Name of the bank branch where the ATM is located.
- **No of ATMs**: Number of ATMs.
- **City**: City in which the ATM is located.
- **State**: State in which the ATM is located.
- **Country**: Country in which the ATM is located.

### Customers Dimension Table
- **Cardholder ID**: Unique identifier for the cardholder.
- **First Name**: First name of the cardholder.
- **Last Name**: Last name of the cardholder.
- **Gender**: Gender of the cardholder (e.g., male, female, other).
- **ATM ID**: Unique identifier for the ATM that the cardholder uses.
- **Age**: Age of the cardholder.
- **Occupation**: Occupation of the cardholder.
- **Account Type**: Type of account that the cardholder has (e.g., savings, checking, etc.).
- **Is Wisabi**: Boolean flag that indicates whether the cardholder is a customer of Wisabi Bank or another bank.

### Transaction Type Dimension Table
- **TransactionTypeID**: Unique identifier for the transaction type (e.g., 1 for withdrawal, 2 for savings, 3 for balance enquiry, 4 for transfer).
- **Transaction Type**: Name of the transaction type (e.g., "withdrawal", "savings", "balance enquiry", "transfer").

### Hour Dimension Table
- **Hours**: Hour of the day (0-23).
- **Hour Start Time**: Time at which the hour begins (e.g., 12:00 AM for hour 0).
- **Hour End Time**: Time at which the hour ends (e.g., 1:00 AM for hour 0).

### Calendar Dimension Table
- **Date**: Date in YYYY-MM-DD format.
- **Quarter**: Quarter of the year in which the date falls (e.g., Q1 for January-March, Q2 for April-June, etc.).
- **Month**: Month in which the date falls (e.g., 1 for January, 2 for February, etc.).
- **Month Name**: Name of Month (E.g January, February, etc.).
- **Day**: Day of the week in which the date falls (e.g., Monday, Tuesday, etc.).
- **Is Holiday**: Boolean flag that indicates whether the date is a public holiday.
- **Day Name**: Name of Day (E.g Monday, Tuesday, etc.).
- **Week of Year**: Week of Year (From 1 to 54).
- **Year**: Year (2022).
- **Start of Month**: Start of Month for each date value.

This comprehensive dataset includes various dimensions and facts crucial for conducting in-depth analysis of Wisabi Bank's ATM transactions.

## Conclusion

The Wisabi Bank ATM Transaction Analysis project is a pivotal endeavor that promises to enhance the bank's understanding of its transaction data. The external consultant will collaborate closely with the Wisabi Bank team to ensure the project's success and deliver the anticipated results.

