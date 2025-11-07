[README.md](https://github.com/user-attachments/files/23423846/README.md)
# 🐍 Python If, Else, Elif Statements and Login System

This repository contains examples and exercises demonstrating how to use **conditional statements** in Python — including `if`, `elif`, and `else` — and a small **login system** built using **nested if/else statements**.

---

## 📘 Project Overview

The notebook introduces different forms of decision-making in Python:

1. **Simple `if` statement**
2. **`if / else` statement**
3. **`if / elif / else` chain**
4. **Nested `if / else` statements**

It ends with a **Login System** project that allows users to:
- Enter their email and password.
- Validate credentials using nested conditions.
- Handle incorrect inputs gracefully.

---

## 🚀 Features

✅ Demonstrates basic conditional logic  
✅ Shows multiple practical examples  
✅ Includes a real-world login simulation using nested if/else  
✅ Beginner-friendly and well-commented code  

---

## 📂 Files

- `if, else, elif statement and login system.ipynb` – Main Jupyter Notebook containing all Python examples and the login system code.

---

## 💡 Example Snippet

```python
Email = input("Enter your email:")
if '@' in Email:
    Password = input("Enter your password:")
    if Email == "uxman00021@gmail.com" and Password == '6543210':
        print("Login Successful")
    elif Email == 'uxman00021@gmail.com' and Password != '6543210':
        password = input('Enter your password again:')
        if password == '6543210':
            print("Login Successful")
        else:
            print('Incorrect password again.')
    else:
        print("Enter correct information")
else:
    print("Your email is not correct")
```

---

## 🧠 What You’ll Learn

- How Python makes decisions using `if`, `elif`, and `else`
- How to build nested conditional logic
- How to simulate a login system without external libraries

---

## 🛠️ Requirements

- Python 3.x  
- Jupyter Notebook (optional, for running `.ipynb` file)

Install Jupyter using:

```bash
pip install notebook
```

Then launch it:

```bash
jupyter notebook
```

---

## 📚 Resources

- [Official Python Documentation – if statements](https://docs.python.org/3/tutorial/controlflow.html#if-statements)
- [Python Input and Output](https://docs.python.org/3/tutorial/inputoutput.html)

---

## 👨‍💻 Author

**Muhammad Usman Khan**  
Student – Generative AI & Chatbot Course by SMIT Sylani Wefare  
*Instructor: Engr Muhammad Junaid Riaz*

---

## 🏁 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/usman0021/If-Else-Elif-Statements-and-Login-System-using-python
   ```
2. Open the notebook in Jupyter.
3. Run each cell to see examples of Python conditional logic.
4. Try the login system at the end!

---

⭐ **If you found this helpful, star the repo on GitHub!**
