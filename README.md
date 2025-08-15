# Discount Calculator

A tiny Python CLI tool that computes the final price after a discount. If the discount percentage is 20% or higher, it applies the discount; otherwise, it returns the original price.

---

## Features

- No external dependencies (runs with Python 3.x)
- Simple command-line prompts for price and discount
- Handles decimal values
- Formats output to two decimal places
- Easy to customize (change the discount threshold if needed)
- Graceful handling of non-numeric input

---

## Getting Started

1. Prerequisites: Python 3.x installed on your system.
2. Create a file named `discount_calculator.py` and copy the code from the README (or download the project).

---

## How to Use

Run the script and follow the prompts.

- If the discount is 20% or more, the final price is shown.
- If the discount is less than 20%, the original price is shown with a message.

Example run:

- Enter the original price of the item: 120
- Enter the discount percentage: 25
- Output:
  - The final price after applying the discount is: $90.00

Example where no discount is applied:

- Enter the original price of the item: 100
- Enter the discount percentage: 15
- Output:
  - No discount applied. The original price is: $100.00
