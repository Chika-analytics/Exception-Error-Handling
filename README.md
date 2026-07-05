# Exception Handling & Debugging Errors in Python

A beginner-friendly Python project that demonstrates how to validate user input and handle errors gracefully using Python's built-in exception handling system.

The program simulates a simple user registration process where users are required to enter a valid username, email address, and password. Each input is validated, and descriptive error messages are displayed whenever an invalid value is entered.

# Project Overview

This project was built to strengthen my understanding of:

- Exception handling using `try` and `except`
- Raising custom exceptions with `raise`
- Writing reusable validation functions
- User input validation
- Basic debugging practices
- Creating cleaner and more reliable Python programs

Instead of allowing the program to crash when invalid data is entered, exceptions are raised and handled gracefully, improving the user experience.

# Features

- Username validation
- Email format validation
- Password length validation
- Custom `ValueError` exceptions
- Friendly error messages
- Successful registration confirmation

# Concepts Practiced

- Functions
- Conditional statements
- String validation
- Exception handling
- `raise`
- `try`
- `except`
- User input
- Debugging

# Project Structure

```
Exception Handling_Debugging_Errors.ipynb
```

# How It Works

The program asks the user to provide:

1. Username
2. Email address
3. Password

Validation rules:

# Username
- Must contain at least **5 characters**

# Email
- Must contain:
  - `@`
  - `.`

# Password
- Must contain at least **8 characters**

If every validation passes:

```
Registration successful!
```

Otherwise, the program displays the appropriate error message without crashing.

# Example Output

# Successful Registration

```
Enter username: Chika123
Enter email: chika@gmail.com
Enter password: mypassword123

Registration successful!
```

# Invalid Username

```
Enter username: Tom

Registration failed: Username must be at least 5 characters long
```

# Invalid Email

```
Enter email: chikagmail.com

Registration failed: Invalid email format. Must contain '@' and '.'
```

# Invalid Password

```
Enter password: pass

Registration failed: Password must be at least 8 characters long
```

# Possible Improvements

Future versions could include:

- Strong password validation
- Password confirmation
- Continuous prompting until valid input is entered
- Email validation using regular expressions
- Storing registered users in a file or database
- Multiple user registration

# Lessons Learned

This project helped reinforce the importance of writing programs that can anticipate and handle errors gracefully. I gained practical experience creating custom validation functions, raising exceptions with meaningful messages, and using `try`/`except` blocks to prevent unexpected program crashes.

# Technologies Used

- Python 3
- Jupyter Notebook

# Author

**Eze Chika**

Aspiring Data Scientist documenting my Python learning journey through hands-on projects and continuous practice.

Feel free to connect with me on LinkedIn and explore my GitHub repositories.
