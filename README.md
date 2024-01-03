# Login-Form
First C++ build 


# User Authentication System

This simple C++ program provides a basic user authentication system with features like sign-up, login, and password recovery. User data is stored in a text file (loginData.txt), and the program allows users to create accounts, log in, and recover passwords.

## How to Use

Login (Option 1): Enter your username and password to log in. If the credentials are correct, the program will display your account information.
Sign-Up (Option 2): Create a new account by providing a username, email address, and password. Your data will be stored in the loginData.txt file.
Forgot Password (Option 3): Recover your password by entering your username and email address. If the information matches an existing account, the program will display the password.
Exit (Option 4): Choose this option to exit the program.
File Structure

loginData.txt: This text file stores user information in the format username*email*password. Each user's data is stored on a new line.
Important Notes

User data is stored in plain text in the loginData.txt file. In a real-world scenario, it is recommended to use secure methods for storing and handling user credentials.
This program uses simple file I/O for data storage. For improved security and efficiency, consider using databases or more advanced storage solutions.
Feel free to modify and enhance this program according to your needs and security requirements.