# Password Management System

## Overview

This C program is designed to help users set a strong password while ensuring that it meets specific security criteria. It checks for the inclusion of uppercase letters, lowercase letters, digits, and special characters, as well as ensuring the password is of a minimum length.

## Features

- Prompts the user to set a password with specific strength requirements.
- Validates the password to ensure it meets the criteria.
- Asks the user to confirm the password and checks for a match.
- Provides feedback on the password's strength and length.
- Outputs a success message upon successful password setting.

## Requirements

- A C compiler (e.g., GCC).
- Basic understanding of C programming.

## How to Compile and Run

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/password-management.git
   cd password-management
   ```

2. **Compile the code:**

   ```bash
   gcc -o password_management password_management.c
   ```

3. **Run the program:**

   ```bash
   ./password_management
   ```

## Usage

1. The program will prompt you to enter a password. 
2. Ensure your password meets the following criteria:
   - Minimum of 8 characters.
   - At least one uppercase letter.
   - At least one lowercase letter.
   - At least one digit.
   - At least one special character (e.g., `!@#$%^&*()`).
3. After entering the password, you will be asked to confirm it.
4. If the passwords match, the program will display the length of your password and a success message.

## Example

```
PASSWORD MANAGEMENT SETTINGS
Set your password (minimum 8 characters, must include upper, lower, digit, and special character): Abc123!
Confirm your password: Abc123!
Passwords match!
Your password length is: 8
Your password 'Abc123!' has been set successfully.
```

## Contributing

If you'd like to contribute to this project, please fork the repository and submit a pull request with your changes.

