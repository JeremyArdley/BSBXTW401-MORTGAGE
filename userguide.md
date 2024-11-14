Here is a user guide for the mortgage calculator Python application as described in the provided code. This guide will help users understand how to use the application effectively.

### User Guide: Mortgage Calculator

#### Introduction
The mortgage calculator is a Python application designed to help clients determine their monthly mortgage payments based on various input parameters including mortgage length, interest rate, and down payment. This tool is ideal for those planning their finances for a home purchase.

#### System Requirements
- Python 3.x installed on your system
- No external libraries required; uses Python’s built-in `math` module

#### How to Run the Program
1. Save the provided Python code in a file with a `.py` extension, for example, `mortgage_calculator.py`.
2. Open a terminal or command prompt.
3. Navigate to the directory where the file is saved.
4. Run the program by typing `python mortgage_calculator.py` and press Enter.

#### Application Menu
When you run the application, you'll be greeted with the following menu:

```
##############################################
             Mortgage Calculator           
1. Provide the length of the mortgage, interest rate and down payment.
2. Exit.
```

#### Usage Instructions

1. **Provide Mortgage Details**:
    - Select option `1` to enter the mortgage details.
    - Follow the prompts to input:
      - **Property Price**: Enter the total cost of the property. The price should be greater than $100,000.
      - **Length of the Mortgage**: Enter how many years the mortgage will last, between 1 and 30 years.
      - **Interest Rate**: Provide the annual interest rate as a percentage (e.g., entering `5` for 5%).
      - **Down Payment**: Input the amount you will pay upfront. This value should not be negative and cannot exceed the property price.

2. **Exit**:
    - Select option `2` to close the application.

#### Functionality Details

- **`calculate_monthly_payment`**: Calculates the monthly payment based on the principal (property price minus down payment), the annual interest rate (converted to a monthly rate), and the total number of payments (duration in years multiplied by 12).

#### Output
- After entering all required data, the program will display the monthly payment amount rounded to two decimal places.
- If you choose to exit, the program will print a goodbye message and terminate.

#### Error Handling
- The application handles incorrect inputs by prompting the user to re-enter the data. This includes non-numeric entries and values that do not meet specified criteria (e.g., negative numbers where not allowed, or interest rates and durations outside acceptable ranges).

#### Authors
- **Jeisson N** and **Eyerusalem Desalegn** designed and developed this application as part of their project work.

This guide should help you navigate and utilize the mortgage calculator for your financial planning needs. If you have any questions or require further assistance, refer to the comments within the code or contact the authors.
