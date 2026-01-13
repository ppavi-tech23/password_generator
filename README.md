# password-generator 🔐

A simple Python password generator that creates secure random passwords with options for length, symbols, and uppercase letters. Great for beginners learning string handling, randomness, and function design in Python.

---

## 🎯 How It Works

- Generates a random password of given length (e.g., 15 characters).  
- You can choose whether to include:
  - Uppercase letters (`A-Z`)
  - Symbols (punctuation like `!@#$%`)
- Uses `secrets` module for cryptographically strong randomness.

Example output:
1 -> K9#mP2!xQ8@vLw (U: True, S: True)
2 -> 7nR$pX1qW4&kTm (U: True, S: True)
3 -> 5bG!sN9@rL2#vP (U: True, S: True)
4 -> 3xM8@kL1!pN7#q (U: True, S: True)
5 -> 6tR!mK9@vL2#nP (U: True, S: True)

text

---

## 🐍 How to Run

Make sure you have Python 3 installed, then:

```bash
python password_generator.py
This will generate and print 5 sample passwords with uppercase and symbols.

To customize:

Change length, symbols, and uppercase in the generate_password() call inside if __name__ == '__main__':.

📂 Files
password_generator.py – The main password generator script.

🌟 Why This Project?
Great for practicing:

Functions with parameters and return values

String handling and character checks

Using string and secrets modules

Simple boolean logic and loops

Easy to extend (e.g., add a CLI, GUI, or save passwords to a file).

📜 License
This project is open source and available under the MIT License. Feel free to use, modify, and share it!

text
undefined
