# College_management_system

## Overview

The College Management System is a Python-based application that helps manage colleges, students, and teachers. It enables administrators to create colleges, add teachers and students, and securely display their details with OTP (One-Time Password) verification. This system provides a simple menu-driven interface for interaction and uses email-based OTP for secure access control.

## Key Features

- **Create Colleges:** Assigns unique IDs and names to colleges.
- **Add Teachers:** Add teachers with their subject specialization, email, and OTP-based verification.
- **Add Students:** Add students to the system with their branch and email, secured by OTP verification.
- **Display Teacher and Student Details:** View the details of teachers and students associated with a college, accessible only after OTP verification.
- **Secure OTP Verification:** Ensures only authorized users can access sensitive information.

## Technologies Used

- **Python 3.x:** Main programming language used to build the system.
- **smtplib:** For sending OTP verification emails to users.
- **email.mime:** For formatting OTP emails.
- **random:** For generating random OTPs for user verification.

## Requirements

- Python 3.x
- smtplib (built-in Python library)
- email.mime (built-in Python library)

To install the dependencies, you can use the `requirements.txt` file if needed:

