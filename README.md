# Banking and Finance SQL Project

### Overview
Built an end-to-end Banking Analytics System using MySQL to analyze branches, customers, accounts, transactions, and loans for real-world financial insights.

### Objectives
- To design a complete banking database
- To analyze customer behavior and account types
- To find high-value customers and loan defaulters
- To generate financial reports using advanced SQL

### Database Schema
- **Customers:** cust_id,cust_name,cust_gender,cust_city,cust_DOB,cust_JoinDate.
- **Branches:** branch_id,branch_name,branch_city
- **Accounts:** Acc_id, customer_id, branch_id, Acc_balance, Acc_type
- **Accounts:** Acc_id,cust_id, branch_id, Acc_balance, Acc_type, Acc_Opdate
- **Transactions:** Trans_id,Acc_Id,Trans_Date,Trans_Type,Trans_Amount
- **Loans:** loan_id, cust_id,loan_Type,loan_amount,Loan_IntRate,Loan_Status,Loan_SDate

### Key SQL Concepts Used
- JOINS (INNER, LEFT)
- SUBQUERIES & CTEs
- WINDOW FUNCTIONS (RANK, ROW_NUMBER)
- AGGREGATE FUNCTIONS (SUM, AVG, COUNT)
- GROUP BY, HAVING, CASE WHEN

### Business Questions Solved (Insights)
1. Find top 5 customers with highest balance
2. Find loan defaulters city-wise
3. Monthly transaction summary
4. Customers having both Savings and Loan account
5. Fraud detection - high frequent transactions

### How to Run
1. Open MySQL Workbench
2. Run the `Banking_Finance_SQL_Project.sql` file
3. Execute the queries

### Tools
- MySQL Workbench
 
---
**Author:** Dattatray Masane | Aspiring Data Analyst
