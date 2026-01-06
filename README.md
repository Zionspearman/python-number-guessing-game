# 🧠 Python Number Guessing Game

A Python-based command-line game that reinforces foundational programming concepts such as user input validation, loops, conditional logic, and random number generation.

---

## 📄 View Full Report
👉 [Python Number Guessing Game.docx](https://github.com/user-attachments/files/24454106/Python.Number.Guessing.Game.docx)


---

## 📌 Project Overview
This project is a Python number guessing game where the user defines a numeric range and attempts to guess a randomly generated number. The program provides feedback after each guess, indicating whether the guess is too high or too low, and continues until the correct number is guessed.

The project emphasizes **defensive programming**, **controlled program flow**, and **clear user feedback**, making it a strong introductory Python project with real-world relevance.

---

## 🎯 Objectives
- Practice accepting and validating user input  
- Implement conditional logic for decision-making  
- Use loops for repeated user interaction  
- Generate random numbers dynamically  
- Track user attempts and display results  
- Prevent program crashes through input validation  

---

## 🛠 Tools & Environment
- **Language:** Python 3  
- **Library:** `random`  
- **IDE:** Visual Studio Code  
- **Execution:** Windows PowerShell / Command Line  

---

## ⚙️ Program Logic
1. Prompt the user to enter a valid number to define the guessing range  
2. Validate input to ensure it is numeric and greater than zero  
3. Generate a random number within the selected range  
4. Enter a guessing loop that:  
   - Accepts guesses  
   - Validates guesses  
   - Provides feedback (too high / too low)  
   - Tracks attempts  
5. Exit the loop once the correct number is guessed and display results  

---

## 🚫 Input Validation
- Non-numeric input is detected using `.isdigit()`  
- Invalid input triggers an error message  
- The program safely exits using `quit()` when requirements are not met  

This ensures clean execution and prevents runtime errors.

---

## 📊 Example Output
```text
Enter a number: 20
Make a guess: 10
Too low!
Make a guess: 15
Too high!
Make a guess: 13
Correct! You guessed the number in 3 tries.
🧠 Key Concepts Demonstrated
User input handling and validation

Conditional logic (if / else)

Loop control with while True

Random number generation

Defensive programming practices

Attempt tracking and program termination
Handle negative guesses during gameplay

Convert the game into a GUI application
