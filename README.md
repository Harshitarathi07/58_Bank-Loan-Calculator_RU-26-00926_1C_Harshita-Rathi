# Bank Loan Calculator

 Project Information:-
- Problem Statement No.: 58
- Project Title: Bank Loan Calculator
- Programming Language: Python 3
- Concepts Used: Functions, Operators, Conditional Statements and EMI Formula.

 Project Description:-
The Bank Loan Calculator is a Python-based program that calculates the monthly EMI (Equated Monthly Instalment), total payable amount and total interest for a bank loan.
It also checks whether an applicant is eligible for the loan based on their monthly income.

Features:-
- Calculates monthly loan EMI.
- Calculates total payable amount.
- Calculates total interest.
- Checks loan eligibility based on monthly income.
- Handles zero-interest loans.
- Validates user inputs.
- Displays results up to two decimal places.

EMI Formula:-

For loans with interest:

EMI = P × r × (1+r)^n / ((1+r)^n - 1)

Where:
- P = Principal loan amount
- r = Monthly interest rate
- n = Loan tenure in months

For zero interest:

EMI = Principal / Number of Months

Eligibility Criteria:-
The applicant is eligible if:

EMI ≤ 40% of Monthly Income

Otherwise, the loan is not eligible.

Technologies Used:-
- Python 3
- Visual Studio Code
- GitHub

How to Run:-
1. Download or clone this repository.
2. Open the project in Visual Studio Code.
3. Run the Python file using the terminal.

```bash
python bank_loan_calculator.py
```

Project Structure

```text
Bank-Loan-Calculator/
│
├── Codebase/
│   ├── README.md
│   └── bank_loan_calculator.py
│
├── testcases/
│
└── README.md
```

Test Cases:-
The project was tested using four test scenarios:

1. Normal Input
2. Boundary / Minimum Input (Zero Interest)
3. Invalid Input
4. Different Valid Scenario (Loan Not Eligible)

Learning Outcomes:-
- Understanding Python functions.
- Applying mathematical formulas in programming.
- Using conditional statements.
- Handling different input scenarios.
- Testing and debugging Python programs.


