# CodeAlpha_Login-Registration
🔐 Login & Registration System (C++)

A simple console-based User Login and Registration System built using C++.
This program validates user input such as first name, last name, email and password, ensuring secure sign-up and authentication.
New users must register first, while existing users can directly log in.

All logic — registration, login, input validation and verification code generation — is implemented inside the program 

Login_Registration

.

✨ Features
Module	Description
➕ New User Registration	Create new account after validation
📧 Email Validation	Ensures correct structure using @ & .
🔐 Strong Password Check	Must contain uppercase, lowercase, number & special character
✔ First/Last Name Validation	Must start with capital letter
🆔 Email Verification	Generates random 4-digit OTP for verification
🔑 Login System	Username + password authentication
🧩 Functions Overview
Function	Purpose
NewRegister()	Main registration workflow
Login()	Handles user login
validfirstname() / validlastname()	Validates names format
validEmail()	Validates email structure and rules
validpassword()	Checks password strength rules
verificationcode()	Generates & verifies 4-digit OTP

All functions are defined in Login_Registration.cpp and interact to provide a full working system 

Login_Registration

.

🔐 Password Requirements

A valid password MUST contain:

Condition	Required
Length	8–15 characters
Uppercase letter	✔
Lowercase letter	✔
Number	✔
Special char (@ # _)	✔

If any condition fails → user must re-enter password ✔

🏗 Project Structure
📁 Login-Registration-System
│── Login_Registration.cpp   # Main Program Source Code
│── README.md                # Documentation

▶ How to Run
1. Clone the Repository
git clone https://github.com/Priyanshumkjee/CodeAlpha_Login-Registration
cd Login-Registration-System

2. Compile the Code
g++ Login_Registration.cpp -o login_app

3. Execute
./login_app

🔍 Program Flow
Welcome!
↓
New user? → Yes → Validate → Register → OTP Verify → Login
                ↳ No → Direct Login

📌 Future Enhancements (optional ideas)

You can improve this project by adding:

✔ File handling for storing user accounts
✔ Masked password input
✔ Multiple user login records
✔ Account recovery via email
✔ GUI / Web version

If you want, I can build any of these for you — just ask! 😊

⭐ Support

If you found this useful:

🌟 Star the repository
🔄 Fork & improve it
💬 Raise issues or suggestions
