# Password Strength Checker

## Project Description

This is a Python-based Password Strength Checker that evaluates the strength of a password entered by the user.

The program asks the user to enter and confirm their password. It checks whether both passwords match using the hmac.compare_digest() function. If they match, it evaluates the password based on its length and the presence of uppercase letters, numbers, and special characters.

The password is then classified into three levels:
- WEAK – Password is shorter than 8 characters or does not meet the required conditions.
- MEDIUM – Password contains at least one of the required character types (uppercase letters, numbers, or symbols).
- STRONG – Password contains uppercase letters, numbers, and symbols and is at least 8 characters long.

The program also provides recommendations to help users improve their password strength.

## How to Run

Requirements:
- Python 3

Steps:
1. Make sure Python 3 is installed.
2. Open the Python file using Python IDLE or another Python editor.
3. Run the program.
4. Enter your password and confirm it when prompted.

No additional libraries need to be installed because the program uses Python's built-in hmac module.