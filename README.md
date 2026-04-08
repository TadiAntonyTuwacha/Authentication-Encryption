# Authentication-Encryption
🔹 Project Description

This project is a Python-based login system built with a graphical user interface using Tkinter. It incorporates input validation and basic encryption techniques to simulate secure authentication. The system validates user credentials and applies a Caesar Cipher to protect passwords during comparison.

🔹 Key Features
GUI-based login interface using Tkinter
Email validation using regular expressions
Strong password validation (uppercase, lowercase, digit, special character)
Password encryption using Caesar Cipher
Secure login verification logic
User-friendly error and success messages
🔹 Tech Stack
Python
Tkinter (GUI development)
Regex (re module for validation)
Basic encryption (Caesar Cipher)
🔹 How It Works
User enters email and password
Email is validated using a regex pattern
Password is checked against strong security criteria
Password is encrypted using Caesar Cipher
Encrypted input is compared with stored encrypted credentials
System returns login success or failure message
🔹 Security Concepts Demonstrated
Input validation and sanitization
Password policy enforcement
Basic encryption techniques
Authentication logic
Error handling without exposing sensitive data
🔹 Limitations
Uses Caesar Cipher (not secure for real-world use)
Hardcoded credentials (not scalable)
No database integration
🔹 Future Improvements
Implement secure hashing (e.g., bcrypt instead of Caesar Cipher)
Store credentials in a database
Add multi-factor authentication (MFA)
Improve UI/UX design
Add account registration and password reset functionality
🔹 Learning Highlights
Building GUI applications in Python
Applying cybersecurity fundamentals in authentication systems
Using regex for validation
Structuring real-world login workflows
