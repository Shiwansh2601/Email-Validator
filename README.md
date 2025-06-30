

# 📧 Email Validation Script in Python

This is a **simple email validator** written in Python that performs various checks to determine if a given email address is valid based on common formatting rules. It ensures that user input follows proper email syntax without using any external libraries or regular expressions.

---

## ✅ Features

* ✅ Validates structure and format of an email
* ✅ Checks for:

  * Minimum length of 6 characters
  * Alphabet character at the beginning
  * Single `@` symbol
  * Proper domain format (`.com`, `.in`, etc.)
  * No whitespaces
  * No uppercase letters
  * Only allowed special characters: `_`, `.`, `@`

---

## 🛠️ Validation Logic Overview

The script performs validation in the following order:

```
1. Checks email length (>=6)
2. Ensures the email starts with a lowercase alphabet
3. Validates presence and count of '@'
4. Checks for valid domain endings like .com or .net
5. Iterates through each character to ensure:
   - No whitespace
   - No uppercase letters
   - Only allowed special characters
6. Final output: Right or Wrong Email based on the checks
```

---

## 🧰 Requirements

No external libraries are needed. The script runs on:

* Python 3+

---

## 🚀 How to Use

1. Clone or download the Python file.
2. Run the script:

   ```bash
   python email_validator.py
   ```
3. Input your email when prompted.

---

## 🧪 Example

### ✅ Valid Input:

```
Enter your Email : example_user123@gmail.com  
Right Email...
```

### ❌ Invalid Input:

```
Enter your Email : Example User@Gmail.com  
wrong Email 5
```

---

## ⚠️ Error Messages Explained

| Error Code    | Reason                                              |
| ------------- | --------------------------------------------------- |
| wrong Email 1 | Email is too short (less than 6 characters)         |
| wrong Email 2 | First character is not a lowercase letter           |
| wrong Email 3 | Invalid or multiple '@' characters                  |
| wrong Email 4 | Invalid domain format (e.g., missing `.com`)        |
| wrong Email 5 | Contains space, uppercase, or disallowed characters |

---

## 📄 License

This project is open-source and licensed under the MIT License.




