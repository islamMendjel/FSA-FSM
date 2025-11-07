# 🔤  Finite State Machine (FSM) and Finite State Automaton (FSA)

A foundational C program that implements a finite automaton to analyze and classify words from a text file based on their composition of letters and digits.

---

## 📚 Features

- Implements a finite automaton with six states (`q0` to `q5`).
- Classifies words into:
  - **Accepted**: Words that are either composed solely of digits with even length or start with a letter followed by a mix of letters and digits.
  - **Rejected**: Words that do not meet the above criteria.
- Utilizes file I/O to read input from `test.txt`.
- Handles various delimiters such as spaces, punctuation, and newlines.
- Outputs the classification of each word along with the state transitions.

---

## 🛠️ Usage

1. **Prepare the Input File**:
   - Create a text file named `test.txt` in the same directory as the program.
   - Populate it with words or sentences to be analyzed.

2. **Compile the Program**:
   ```bash
   gcc main.c -o automaton
