# OTP Verification System – Python Capstone Project

This is a basic **OTP (One-Time Password) verification system** developed as part of my Python capstone project for Odin School. The system securely sends a 6-digit OTP to the user's Gmail, and the user must enter it to verify access.

## Features
- Random 6-digit OTP generation  
- OTP sent via Gmail SMTP  
- App password used for secure login  
- Secure input for password using `getpass`  
- 3 chances to enter OTP correctly  
- User-friendly messages and error handling
  
## Technologies Used
- Python 3  
- `random`, `smtplib`, `email.message`, `getpass`  
- Jupyter Notebook / Google Colab

## How to Run the Project
1. Enable 2-step verification in your Gmail account  
2. Generate an **App Password** from Google security settings  
3. Open `OTPVerificationSystem.ipynb` in Colab or Jupyter  
4. Enter your Gmail and App Password when prompted  
5. Enter the OTP received in your Gmail inbox

## Test Scenarios
-  Correct OTP entered → Access granted  
-  Incorrect OTP entered → Tries left  
-  Wrong 3 times → Access denied  
-  Network or credential error → Error message shown

## Files Included
- `OTPVerificationSystem.ipynb` – Main Python notebook with all code blocks

##  Author
**Namratha**
Python Capstone – Odin School  
July 2025
