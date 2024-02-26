# Mobile Applications I Project 2

## Description

This project is a mobile application developed in Xcode using Swift. It includes various features and functionalities tailored to meet specific requirements.

## Functionality

A functionality included in this project is a Swift function named “Payment” that calculates the amount of a mortgage payment. This function utilizes concepts learned in Module 2 and is designed to accurately determine the periodic payment of principal and interest for different loan scenarios.

## Function: Payment Calculation

### The Payment function is designed to take the following inputs:

The amount of the loan in whole dollars (an Int).
The number of payments (e.g., 360 for a 30-year loan) (an Int).
The interest rate per payment period in percent (a positive floating-point number).
The function returns the correct value (in dollars and cents, a Float) of the periodic payment of principal and interest, ignoring escrow accounts, taxes, and insurance.

## Scenarios
The Payment function calculates the periodic payment of principal and interest for the following scenarios:

### 2-month loan:
Loan amount: $20,000
Annual Percentage Rate (APR): 4.4%
Compounded monthly
### 30-year loan:
Loan amount: $150,000
Annual Percentage Rate (APR): 5%
One annual payment each year for 30 years
### Note
When passing the interest rate to the function, ensure it is per payment period. For instance, if the period is one year and the interest rate is quoted as an annual rate (APR), you just pass the APR. However, if you have an annual interest rate and the period is monthly, divide the rate by 12 before passing it to the function.

## Usage

### To use the Payment function in your project, follow these steps:

Copy the function implementation into your Swift file.
Call the function with the required parameters: loan amount, number of payments, and interest rate.
Receive the calculated payment amount as the return value.

## Testing

To ensure the accuracy of the Payment function, you can compare its output with results from reputable online loan calculators.

## Payment Playground

Additionally, a Payment playground is provided in Xcode using Swift. You can use this playground to experiment with the Payment function and understand how it works.

## Resources

Refer to appropriate videos or online sources for understanding the mathematics behind the payment calculation.
Utilize loan calculators online to cross-verify the accuracy of the Payment function.
