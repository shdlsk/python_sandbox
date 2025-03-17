# Interest Calculator

This Python project allows you to calculate the earned interest on a savings account, considering taxes and additional monthly deposits. The script computes monthly income, deducts taxes (19%), and updates the account balance accordingly. The results can be saved in a CSV file.

## Features

- Prompt for initial deposit, bank interest rate, monthly deposits, and number of months.
- Calculate monthly interest with tax deduction.
- Display account balance, earned interest, and tax paid each month.
- Option to save results in CSV format.
- Final summary showing total earned interest and taxes paid.

## Installation

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/shdlsk/python_sandbox/tree/main/interest_calculator
    ```

2. Ensure you have Python 3.x installed. You can check the version with:

    ```bash
    python --version
    ```

3. Install any required dependencies (if applicable):

    ```bash
    pip install -r requirements.txt
    ```

## How to Use

1. Clone or download the project.
2. Navigate to the `interest_calculator` folder and run the Jupyter Notebook:


    ```bash
    cd interest_calculator
    jupyter notebook
    ```

    The script will ask for the following inputs:
    - Initial deposit (amount in PLN)
    - Monthly deposits (amount in PLN, if you don't plan add - type 0)
    - Bank interest rate (float number in format xx.x)
    - Number of months (int number)

3. After the calculations are completed, the script will prompt you to save the results in a CSV file.

## Example Output:
```text
Current date: 17 March 2025

Results for 8 months starting from March 2025:
March 2025
Earned: 2.03 PLN
Tax paid: 0.47 PLN
Balance: 1002.02 PLN

April 2025
Earned: 3.04 PLN
Tax paid: 0.71 PLN
Balance: 1505.07 PLN

May 2025
Earned: 4.06 PLN
Tax paid: 0.95 PLN
Balance: 2009.13 PLN

June 2025
Earned: 5.08 PLN
Tax paid: 1.19 PLN
Balance: 2514.21 PLN

July 2025
Earned: 6.1 PLN
Tax paid: 1.43 PLN
Balance: 3020.31 PLN

August 2025
Earned: 7.13 PLN
Tax paid: 1.67 PLN
Balance: 3527.44 PLN

September 2025
Earned: 8.16 PLN
Tax paid: 1.91 PLN
Balance: 4035.6 PLN

October 2025
Earned: 9.18 PLN
Tax paid: 2.15 PLN
Balance: 4544.78 PLN


Total earned interest (after tax): 44.78 PLN
Total tax paid: 10.5 PLN

Data was not saved.
```