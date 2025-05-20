# Snack Stack Takeout Order System

## Description
The Snack Stack Takeout Order System is a command-line Python application that allows customers to browse a digital menu, place food orders by selecting item numbers, specify quantities, and receive an itemized receipt. It is designed for accessibility and ease-of-use, with robust input validation and a readable, formatted output.

## Table of Contents
- [Motivation](#motivation)
- [Usage](#usage)
- [License](#license)
- [Learning](#learning)
- [Standout](#standout)
- [Questions](#questions)
- [Demo](#demo)
- [GitHubRepo](#githubrepo)
- [Key_Features](#key_features)
- [RunApp](#runapp)

## Motivation
The goal of this project was to create an accessible and user-friendly restaurant ordering experience for customers who prefer not to speak or hear. It offers a digital alternative to ordering in person by presenting a full menu, capturing customer selections, handling input errors gracefully, and printing a clean receipt.

## Usage
This app runs in a terminal and allows a user to:
- View a numbered restaurant menu (category, item, price)
- Select items by number and specify quantity
- Re-order additional items or finish
- Automatically default invalid quantities to 1
- Receive an itemized receipt with total cost

## License
This project is licensed under the None license.

## Learning
I improved my skills with nested dictionaries, list comprehensions, loops, and conditionals in Python. I also practiced validating user input and formatting output for clarity. This project reinforced how to structure a Python CLI app and separate logic for readability and maintainability.

## Standout
What makes this project stand out:
Strong accessibility use case (no voice needed)
Default fallback for invalid quantity inputs
Clean receipt layout with total calculation
Menu rendered dynamically from nested dictionary
Defaults to 1 quantity if <=0 or invalid input
All logic follows clearly marked TODO comments to aid learning

## Questions
If you have any questions, please reach out to me via:
- GitHub: [Fortunate122](https://github.com/Fortunate122)
- Email: davidsaldana122@gmail.com

## Demo
https://app.screencastify.com/v2/watch/3ZBWjr7MQyqsgVLPudPZ


## GitHubRepo
https://github.com/Fortunate122/Snack_Stack

## Key_Features:
- Nested dictionary structure for menu
- Order tracked as a list of item dictionaries
- Input validation for item numbers and quantities
- Well-formatted receipt layout

## RunApp:
```bash
python order_system.py
