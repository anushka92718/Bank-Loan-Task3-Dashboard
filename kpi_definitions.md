# KPI Definitions – Bank Loan Report

## 📊 Core KPIs

1. Total Loan Applications  
   = COUNT(id)

2. Total Funded Amount  
   = SUM(loan_amount)

3. Total Amount Received  
   = SUM(total_payment)

4. Good Loan Percentage  
   = (Good Loans / Total Loans) * 100  
   WHERE loan_status IN ('Fully Paid', 'Current')

5. Bad Loan Percentage  
   = (Bad Loans / Total Loans) * 100  
   WHERE loan_status = 'Charged Off'

6. Average Interest Rate  
   = AVG(int_rate) * 100

7. Average DTI  
   = AVG(dti) * 100
