Chat Application - Login System
Project Description

This project is a simple Java-based login and registration system. It allows users to:

Register with a username, password, and South African phone number
Log in using their credentials
Receive feedback messages based on their login status

The system includes input validation and unit testing to ensure correctness.

Features
Username validation (must contain "_" and be ≤ 5 characters)
Password complexity validation:
Minimum 8 characters
At least 1 uppercase letter
At least 1 number
At least 1 special character
Phone number validation (must start with +27 and be 12 digits)
User registration system
Login authentication
Console-based user interaction
Unit testing using JUnit

Unit Testing

Unit tests were created using JUnit 5 to test:

Username validation
Password complexity
Phone number validation
User registration
Login functionality
Login status messages

All tests pass successfully after fixing logic errors in the Login class.

Project Structure
com.mycompany.chatapp
│
├── Login.java        // Handles validation and login logic
├── MainApp.java      // Runs the application (user interaction)
└── LoginTest.java    // Unit tests for the Login class

How to Run the Program
Open the project in NetBeans or any Java IDE
Run MainApp.java
Follow the prompts:
Enter registration details
Then log in using the same details

How It Works
User registers by entering:
Username
Password
Phone number
The system validates all inputs:
If invalid, an error message is shown
If valid, the user is registered
User logs in:
If credentials match, a welcome message is displayed
If incorrect, an error message is shown

Known Fixes Applied

The following issues were fixed in the original code:

Username validation incorrectly allowed all inputs
Password validation did not check for numbers
Password length condition was incorrect
Phone number validation allowed incorrect lengths
