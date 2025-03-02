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


## How It Works

1. **Create College:**
   - Input a unique college ID and name to create a new college.
   
2. **Add Teacher:**
   - Input the college ID, teacher’s name, email, and subject specialization.
   - An OTP will be sent to the teacher's email for verification before adding them to the system.
   
3. **Add Student:**
   - Input the college ID, student’s name, email, and branch.
   - An OTP will be sent to the student's email for verification before adding them to the system.

4. **Display Teacher/Student Details:**
   - Input the college ID to view details of teachers or students associated with that college.
   - Details will be shown only after OTP verification.

5. **Exit:**
   - The user can exit the program at any time.

## Example of OTP Email

When adding a teacher or student, an email will be sent to the provided email address with the following format:


After receiving the OTP, the user will be prompted to enter the OTP code for verification. If the OTP is correct, the teacher or student will be successfully added to the system.

## Security Considerations

- Use a dedicated email account for sending OTPs in a production environment.
- Do not hard-code sensitive information (e.g., email credentials) in the source code. Instead, use environment variables or a configuration file to securely manage credentials.

## Future Improvements

- **Database Integration:** Integrate with a database (e.g., SQLite, MySQL) to persist data across sessions.
- **Graphical User Interface (GUI):** Create a GUI for a more user-friendly experience.
- **SMS OTP:** Implement OTP verification via SMS using third-party services like Twilio.


## License

This project is open-source and available under the [MIT License](LICENSE).




