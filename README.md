**Description**
This repository contains an Excel-based amortization schedule for a mortgage loan with the following details:

Loan Amount: $1,500,000 (after a $70,000 down payment)

Annual Interest Rate: 6.5%

Loan Term: 15 years and 5 months (185 months)

Repayment Start Date: January 2025

The schedule provides a month-by-month breakdown of:

Opening and closing balances

Interest and principal payments

Cumulative interest and principal paid over time

**Key Features**
Dynamic Calculations: Uses Excel formulas to automatically compute monthly payments, interest, and principal allocations.

Visualization: Includes a graphical depiction of the amortization schedule.

Detailed Breakdown: Tracks the loan balance, interest, and principal for each payment period.

**Formulas Used**
Monthly Interest Rate: =D8/12

Monthly Payment: =PMT(K6,K7,-K9)

Loan Amount: =D6-D9 (after down payment)

Monthly Calculations:

Interest: =ROUND(Opening Balance * Monthly Interest Rate, 2)

Principal: =ROUND(Monthly Payment - Interest, 2)

Closing Balance: =ROUND(Opening Balance - Principal, 2)

**Notes**
The schedule rounds values to two decimal places for clarity.

The final payment includes a minor adjustment (-0.02) to ensure the closing balance reaches zero.
