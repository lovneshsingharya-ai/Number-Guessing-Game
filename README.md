# 🎯 Number Guessing Game in C

A simple **Number Guessing Game** made using C.

The computer randomly selects a number between **1 and 100**, and the player has to keep guessing until they find the correct number.

I made this project while learning C programming, mainly to practice **loops, conditions, random numbers, and variables**.

---

## 🎮 How the Game Works

1. The computer generates a random number between **1 and 100**.
2. The player enters a guess.
3. The program gives a hint:
   - If the guess is too high → `Lower number please`
   - If the guess is too low → `Higher number please`
   - If the guess is correct → `Congratulations!!`
4. The game continues until the correct number is guessed.
5. At the end, the program tells you how many guesses you needed.

---

## 💻 Example

```text
Guess the number: 50
Higher number please

Guess the number: 75
Lower number please

Guess the number: 63
Higher number please

Guess the number: 68
Congratulations!!

You guessed the number in 4 guesses.
