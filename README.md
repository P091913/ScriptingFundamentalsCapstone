# ScriptingFundamentalsCapstone

💡 Project Overview

Students will develop a command-line Python application that allows users to:

  - Create user accounts
  - Validate and securely store user data (including passwords)
  - Scrape a public website to gather data (e.g., usernames or emails)
  - Check for possible leaked information using regex
  - Hash and encrypt sensitive data before storing it
  - Export and import data from files


🛡️ Capstone Assignment: Build a Secure User Data Manager with Networking and Cybersecurity

🔍 Overview:
Students will work in groups to build a command-line Python application that simulates a secure user account system, integrates web scraping, implements password encryption and hashing, and uses regex and file I/O to simulate real-world data breach detection and secure credential storage.

This project combines:

  - Python basics
  - Loops & error handling
  - Data structures
  - Encryption, hashing
  - Web scraping & regex leak detection
  - Networking simulations

Step-by-Step Breakdown:

Part 1: Set Up Project Framework (Python Basics, Input/Output, Decisions)
Objective: Create the main menu and basic program flow.

  - Display menu options using print()
  - Use input() to accept user input
  - Use if/else or match/case to handle different choices
  - Display formatted output to confirm user actions

Part 2: Add Looping, Input Validation, and Error Handling
Objective: Make the program interactive and robust.

  - Create a loop to return to the main menu until exit
  - Use while loops for login retries
  - Validate inputs (e.g., password must be 8+ characters, contain number/capital letter)
  - Use try/except to handle errors (e.g., file not found, invalid data)

Part 3: Store User Data with Data Structures
Objective: Save multiple users using appropriate structures.

  - Use a dictionary to store each user's info (username as key, dict of email/password as value)
  - Optionally use lists or tuples for login history or password attempts

Part 4: Implement File Handling & Functions
Objective: Save and retrieve user data from a file.

  - Create functions: register_user(), login_user(), load_data(), save_data()
  - Use a txt file or a database to save encrypted user info
  - Read the file or database on program start and update on save
    
Part 5: Add Password Hashing and Encryption
Objective: Secure sensitive user data.

  - Hash passwords using hashlib
  - Optionally encrypt entire user records using cryptography.fernet
  - Store only hashed/encrypted data in the file

Part 6: Networking & Web Scraping for Leak Check
Objective: Simulate checking for leaked data from a website.

  - Use requests and BeautifulSoup to scrape a mock pastebin site or local HTML file
  - Use regex to extract potential usernames/emails
  - Compare against registered user info and warn if exposed

*** OPTIONAL - WILL REQUIRE RESEARCH ***
Part 7: Simulate a Networked Login Environment (Optional Advanced Challenge)
Objective: Simulate users accessing the system from different "devices".

  - Simulate login attempts with different IPs (hardcoded or randomized)
  - Track login locations/IPs (mocked)
  - Store logs of login attempts in a file


✅ Documentation (1–2 pages explaining your structure, security measures, and testing)
✅ Project Zipped Up
✅ GitHub Repo Link
