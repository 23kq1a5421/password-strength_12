# Password Strength Checker

##  Project Overview

The Password Strength Checker is a beginner-friendly cybersecurity project developed using Python. It evaluates the strength of a password based on different security conditions and classifies it as **Weak, Medium, or Strong**.

The main goal of this project is to encourage users to create strong passwords and improve password security.

##  Features

- Checks password length (minimum 8 characters).
- Identifies uppercase letters.
- Identifies lowercase letters.
- Checks whether the password contains numbers.
- Detects special characters such as @, #, $, and !.
- Classifies passwords into Weak, Medium, and Strong categories.

##  Technologies Used

- **Programming Language:** Python
- **Concepts:** Conditional Statements, Loops, String Methods
- **Python Functions:** `len()`, `isupper()`, `islower()`, `isdigit()`, `isalnum()`, `any()`

##  Project Structure

```text
Password_Strength_Checker/
│
└── password_checker.py
```

##  How It Works

1. The user enters a password.
2. The program checks its length.
3. It checks for uppercase and lowercase letters.
4. It checks for numbers and special characters.
5. A score is calculated based on the satisfied conditions.
6. Finally, the password is classified as Weak, Medium, or Strong.

##  How to Run the Project

**Step 1:** Clone the repository.

```bash
git clone YOUR_REPOSITORY_URL
```

**Step 2:** Open the project folder.

```bash
cd Password_Strength_Checker
```

**Step 3:** Run the Python file.

```bash
python password_checker.py
```

##  Sample Output

**Example 1: Weak Password**

```text
Enter your password: hello
Password Strength: WEAK
```

**Example 2: Medium Password**

```text
Enter your password: Hello123
Password Strength: MEDIUM
```

**Example 3: Strong Password**

```text
Enter your password: Hello@123
Password Strength: STRONG
```

##  Learning Outcomes

- Learned basic password security concepts.
- Understood how to use Python string methods.
- Practiced conditional statements and loops.
- Learned how to evaluate password strength using simple rules.
- Gained practical knowledge of basic cybersecurity.

##  Future Enhancements

- Add a graphical user interface (GUI).
- Add a password visibility option.
- Detect commonly used or compromised passwords.
- Display a password strength meter.

##  Disclaimer

This project is developed for educational purposes. It uses basic password rules and does not provide a complete security assessment or guarantee password safety.

##  Author

**Salma Shaik**

B.Tech – Artificial Intelligence and Data Science

---

⭐ If you find this project useful, feel free to explore and improve it!
