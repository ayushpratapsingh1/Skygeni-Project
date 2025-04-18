# Subscription and Payment Analysis

This project involves analyzing a dataset containing information about subscriptions, payments, and industries, with the goal of deriving meaningful insights for the organization. The analysis covers various aspects like renewal rates, industry trends, inflation rates during renewals, and payment patterns across different methods. The results are presented through data processing, statistical calculations, and visualizations.

## 🛠️ Technologies Used

- **Python 3.7+**
- **Pandas** for data manipulation
- **NumPy** for numerical computations
- **Matplotlib** and **Seaborn** for data visualization

## 📂 Project Files

1. **subscription_information.csv**: Contains details about client subscriptions, including subscription type, start and end dates, and renewal status.
2. **payment_information.csv**: Includes client payment data, payment methods, and amounts paid.
3. **financial_information.csv**: Provides quarterly inflation rates and GDP growth rates.
4. **industrial.csv**: Contains client information related to their industry, company size, and location.

## 🔍 Key Questions

1. **How many Finance Lending and Blockchain clients does the organization have?**
   - We filter the data to identify the number of clients in the "Finance Lending" and "Blockchain" industries.

2. **Which industry in the organization has the highest renewal rate?**
   - By calculating the renewal rate for each industry, we identify the industry with the highest renewal rate.

3. **What was the average inflation rate when their subscriptions were renewed?**
   - We calculate the average inflation rate during the periods when subscriptions were renewed by matching renewal dates to the relevant financial quarters.

4. **What is the median amount paid each year for all payment methods?**
   - We compute the median payment amount for each year across different payment methods to understand trends in payments.

## 📊 Visualizations

- **Line Chart for Median Payment Amount**: A line chart is used to represent the median payment amount each year across all payment methods. This visualization helps to identify payment trends over time.

## 🧹 Data Cleaning

- The dataset had inconsistencies in date formats, which were standardized to avoid errors during analysis. The data was thoroughly cleaned to ensure accuracy and reliability.
