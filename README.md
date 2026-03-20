
# 🔐 Password Strength Checker (Python)

A simple Python program that checks the strength of a password and provides suggestions to improve it.

---

## 🚀 Features
- Checks password strength based on:
  - Length (minimum 8 characters)
  - Uppercase letters
  - Lowercase letters
  - Numbers
  - Special characters
- Gives a strength rating:
  - Weak ❌
  - Medium ⚠️
  - Strong ✅
- Provides suggestions to improve weak passwords

---

## 🛠️ How It Works

The program evaluates your password using regular expressions (`re` module) and assigns a score based on different criteria.

### Strength Criteria:

| Condition                  | Points |
|---------------------------|--------|
| ≥ 8 characters            | +1     |
| Contains uppercase letter | +1     |
| Contains lowercase letter | +1     |
| Contains number           | +1     |
| Contains special character| +1     |

### Final Result:
- **0–2 points** → Weak ❌  
- **3–4 points** → Medium ⚠️  
- **5 points** → Strong ✅  

---

## 📦 Requirements
- Python 3.x  
- No external libraries required (uses built-in `re` module)

---

## ▶️ How to Run

1. Save the file as:
   ```
   Password-checker.py
   ```

2. Run the program:
   ```
   python Password-checker.py
   ```

3. Enter your password when prompted:
   ```
   Enter your password: MyPass123!
   ```

---

## 💡 Example Output

```
Password Strength: Strong ✅
Your password is secure!
```

or

```
Password Strength: Weak ❌
Suggestions to improve:
- Use at least 8 characters
- Add uppercase letters
- Include numbers
```

---

## 🧠 What You Learn
- Basic Python functions
- Using regular expressions (`re`)
- Conditional logic
- User input handling

---

## 🔮 Future Improvements
- Add password entropy calculation
- Create GUI version (Tkinter)
- Add real-time strength meter
- Build a web version

---

## ⚡ What to Remember
- Strong password = mix of **length + variety**
- Always include:
  - Uppercase + lowercase
  - Numbers
  - Special characters
- Avoid common passwords like `123456` or `password`
