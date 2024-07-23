# Income Tax Calculator (Financial Year 2024-2025)

This Python program calculates income tax for the financial year 2024-2025 based on the latest tax slabs and deductions provided by the government. It allows users to input their salary and deducts standard deductions, NPS deductions, and medical deductions before computing the income tax.

## Features

- Calculates income tax based on the following tax slabs for FY 2024-2025:
  - Up to Rs 3,00,000: 0%
  - From Rs 3,00,001 to Rs 7,00,000: 5%
  - From Rs 7,00,001 to Rs 10,00,000: 10%
  - From Rs 10,00,001 to Rs 12,00,000: 15%
  - From Rs 12,00,001 to Rs 15,00,000: 20%
  - Above Rs 15,00,000: 30%

- Allows input of salary to calculate income tax after deducting:
  - Standard deduction: Rs 75,000
  - HRA deduction (if applicable, currently assumed as 0)
  - NPS deduction: Rs 1,00,000
  - Medical deduction: Rs 30,000

## Usage

1. **Installation:**
   - Ensure Python 3.x is installed on your system.

2. **Run the Program:**
   - Open a terminal or command prompt.
   - Navigate to the directory containing `income_tax_calculator.py`.
   - Run the program by typing: `python income_tax_calculator.py`.

3. **Input:**
   - Enter the salary when prompted.

4. **Output:**
   - The program will calculate and display the income tax payable based on the provided salary and deductions.

## Example

Suppose you want to calculate income tax for a salary of Rs 10,00,000 for FY 2024-2025:
- After deducting standard deduction (Rs 75,000), NPS deduction (Rs 1,00,000), and medical deduction (Rs 30,000):
  ```
  taxable_income = 1000000 - 75000 - 100000 - 30000 = 795000
  ```
- Applying the tax slabs:
  - Up to Rs 300,000: 0%
  - From Rs 300,001 to Rs 700,000: (700000 - 300000) * 0.05 = Rs 20,000
  - From Rs 700,001 to Rs 1,000,000: (795000 - 700000) * 0.10 = Rs 9,500
  - Total tax = Rs 20,000 + Rs 9,500 = Rs 29,500


