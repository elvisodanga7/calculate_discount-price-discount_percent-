# Discount Calculator

This is a simple Python program that calculates the final price of an item after applying a discount.  
The discount is only applied if it is **20% or higher**. Otherwise, the original price is returned.

## Features
- Function `calculate_discount(price, discount_percent)` applies discount logic.
- User-friendly prompts for entering item price and discount percentage.
- Handles invalid inputs (non-numeric values).
- Ensures only meaningful discounts (≥ 20%) are applied.

## How It Works
1. The program asks the user to input:
   - The original price of the item.
   - The discount percentage.
2. If the discount percentage is **20% or more**, the discount is applied.
3. If the discount percentage is less than 20%, the program returns the original price.
4. The result is displayed with two decimal places.

## Example Run
