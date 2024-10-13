# Python-Password-Generator
This is a simple Python script that generates a random password with a specified length. The password will always contain at least one lowercase letter, one uppercase letter, one digit, and one special character to ensure a secure password. It also includes functionality to check the strength of the generated password, copy it to the clipboard, and save it to a file.

# Features
* Generate a secure password with a minimum length of 9 characters.
* Ensure that the password contains at least one lowercase letter, one uppercase letter, one digit, and one special character.
* Copy the generated password directly to the clipboard using pyperclip.
* Check the strength of the password (Strong, Medium, or Weak).
* Option to save the password in a text file for future reference.

# Requirements
To run the script, you will need to have Python installed on your system. Additionally, you'll need the following Python packages:
* pyperclip (for copying the password to the clipboard)

```
pip install pyperclip
```

# How to use
* Clone this Repository
* Navigate to the project directory
* Run the code
  ```
  python Password_Generator.ipynb
  ```
# Smaple Output
```
Enter the desired password length: 12
Your Password is: aS9!kZl2@qP1
The password has been copied to your clipboard.
Strong Password
Do you want to save this password? (y/n): y
The password has been saved to generated_password.txt.

```
