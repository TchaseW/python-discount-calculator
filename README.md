# Python Discount Calculator

## About This Project

This project is an object-oriented Python discount calculator that determines the best available price for a product based on different discount strategies and customer membership tiers.

The program evaluates applicable discounts and returns the lowest available price.

## Technologies Used

- Python
- Object-Oriented Programming (OOP)
- Abstract Base Classes

## Programming Concepts Demonstrated

- **Classes and Objects:** Created Product and DiscountEngine classes.
- **Inheritance:** Created discount strategies that inherit from DiscountStrategy.
- **Abstraction:** Used Python's ABC module and abstract methods.
- **Polymorphism:** Implemented different discount methods using a shared interface.
- **Type Hints:** Used Python type annotations.
- **List Comprehensions:** Evaluated available discounted prices.

## Discount Strategies

The program includes three discount strategies:

1. Percentage Discount – Reduces the original price by a percentage.
2. Fixed Amount Discount – Subtracts a fixed dollar amount.
3. Premium User Discount – Provides a 20% discount to premium members.

The DiscountEngine evaluates applicable strategies and selects the lowest price.

## Example Output

For a $50 wireless mouse purchased by a premium user:

```text
Best price for Wireless Mouse for Premium user: $40.00
```

## Testing

The program was executed using the example product and premium customer scenario.

- Original price: $50.00
- Premium discount: 20%
- Final price: $40.00

The program produced the expected output.

## What I Learned

Through this project, I practiced:

- Designing programs using object-oriented programming.
- Creating classes and inheritance relationships.
- Using abstract base classes and abstract methods.
- Implementing multiple discount strategies.
- Comparing calculated values to determine the best price.
- Applying Python type hints and list comprehensions.

## Learning Experience

Completed as part of my Python programming coursework through freeCodeCamp.

## Status

Completed as part of freeCodeCamp coursework.
