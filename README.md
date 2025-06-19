

# Password Strength Analyzer + Custom Wordlist Generator

## 🔐 Overview
This project analyzes the strength of a given password and generates a personalized wordlist for ethical cracking tests based on user input (e.g., name, DOB, pet name).

## 🛠 Features
- Password strength analysis using zxcvbn
- Strength score and estimated crack time
- Custom wordlist generation using permutations and leetspeak
- GUI version using tkinter
- CLI version using standard input

## 📁 Files
- `password_gui.py` — GUI tool with analysis and wordlist generation
- `password_strength_wordlist.py` — CLI version of the same tool
- `enhanced_wordlist.txt` — Output wordlist file

## ▶️ How to Run
### CLI Version:
```bash
python password_strength_wordlist.py
```

### GUI Version:
```bash
python password_gui.py
```

## 📸 Screenshots (add to a /screenshots folder)
- GUI running
- Analysis result
- Popup box after password analysis
