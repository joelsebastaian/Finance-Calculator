# Personal Finance Tracker

#### Video Demo:  [https://youtu.be/GRctJcaQxDM]
#### Description: Finance Calculator

This project is a personal finance tracker that allows users to add, remove, list, and calculate total expenses. It is implemented in Python and uses simple text-based input and output.

## Files

- `project.py`: The main script that contains the main function and the four custom functions: `add_expense`, `remove_expense`, `list_expenses`, and `total_expenses`.
- `test_project.py`: The script containing tests for the custom functions in `project.py`.
- `requirements.txt`: Lists the required libraries for the project.

## Usage

1. Run `project.py` to start the program.
2. Follow the on-screen prompts to add, remove, list, or calculate total expenses.
3. Use the `exit` command to terminate the program.

## Design Choices

The project is designed to be simple and user-friendly, using command-line input and output to interact with the user. The main function serves as the entry point and dispatches commands to the respective functions. Each function performs a specific task, making the code modular and easy to test.

The tests in `test_project.py` ensure that the main functions work correctly. This helps in maintaining code quality and reliability.

