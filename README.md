# Rock-Paper-Scissor---C
This is a console-based Rock Paper Scissors game written in C. The game is played between the user and the CPU for three rounds. It uses random number generation to simulate computer choices and basic conditional logic to decide the winner. This project is created for learning and fun.
# Rock Paper Scissors Game in C 🎮

A simple console-based **Rock Paper Scissors** game built using the **C programming language**, where the user plays against the computer for three rounds.

This project is beginner-friendly and demonstrates the use of functions, conditional statements, loops, and random number generation in C.

---

## 📌 Features
- User vs Computer gameplay
- 3 rounds per game
- Random computer choices using `rand()` and `srand()`
- Score tracking system
- Simple and clean console UI
- Written in pure C (no external libraries)

---

## 🛠️ Technologies Used
- Language: **C**
- Compiler: GCC / Turbo C / Any standard C compiler
- Libraries:
  - `stdio.h`
  - `stdlib.h`
  - `time.h`

---

## 🎯 How to Play
1. Run the program
2. Choose one option:
   - `1` → Rock (R)
   - `2` → Paper (P)
   - `3` → Scissor (S)
3. The computer will randomly choose its option
4. After 3 rounds, the final winner is declared

---

## ▶️ How to Compile and Run

### On Linux / Mac
```bash
gcc rps.c -o rps
./rps
