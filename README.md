# Global Bank- Mortage Load Application Tracker

In this project I have created multi-page Power BI Dashbaord to help Global bank with crucial Business decisions and calculate the mortage loan application scores to decrease the response time for applications.

1. Data Loading

- Data and description for data columns has been provided by the bank in the Microsoft Excel via several worksheets.
- Loaded data using the Power BI power query.

---

2. Data Cleaning

- As per description of columns provided the bank we had to fix some abnormalities in Family status with respect to Duplicate, Redundant values. Refer Image below
  ![Replace Redundant values](<Assets/Replace Redundant Values.png>)

- Handling Outliers in Number of dependent children for eg: 30 child is impractical for an individual values that might have been errorneously entered by the human. Corrected such outliers by replcing it with appropriate values
  ![handling outliers in the dataset](<Assets/Handle Outlier Values in Children.png>)

---

3. Merging the Mortage Applicatio table and Down payment table to include <code>Down payment </code> column corresponding to Application number.

---

4. Add columns for deriving actual Loan Amt using the table columns itself
   <code>Loan Amt = Transction Total - Down Payment</code>

---

5. Mortage Applications: page shows analysis of following (clockwise)
   ![Mortage applications](<Assets/Mortage Application.png>)
   - Application under review
   - Application history
   - Loan acceptance rate over time
   - Loan amount over time

---

6. Branch Performance: page shows analysis
   ![Branch performance](<Assets/Branch Performance.png>)
   - Global bank branch location.
   - Number of loan applications received per branch.
   - Branch ranking by number of applications.
   - Loan acceptance rate per branch.

---

7. Customer characteristic: page shows analysis
   ![Customer characteristics](<Assets/Customer characteristics.png>)
   - Applications by customer characteristics, over time

---

8. Customer Lists: page allows us to view the details of a particular customers loan application(s).
   ![Customer lists](<Assets/Customer lists.png>)
