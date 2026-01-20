Password Strength Checker & Generator
A robust Python-based tool designed to evaluate the security of passwords and generate cryptographically secure alternatives. This project focuses on Regular Expressions (Regex) and Cybersecurity fundamentals.

🚀 Features
Real-time Analysis: Checks password length and character diversity.

Regex Engine: Uses pattern matching to identify digits, uppercase letters, and special symbols.

Smart Scoring: Provides a score from 0-4 based on industry-standard security criteria.

Secure Generator: Uses Python's random and string modules to create high-entropy passwords.

🛠️ Built With
Python 3.x

re module: For pattern matching and validation.

random & string modules: For secure character selection.

📋 How It Works
The architecture follows a simple 3-step process:

Input: User enters a potential password.

Scan: The logic layer runs four distinct Regex checks:

Minimum 8 characters.

At least one digit (0-9).

At least one uppercase letter (A-Z).

At least one special character (!@#$%^&*).

Output: Displays a score and suggests a new password if the score is low.
