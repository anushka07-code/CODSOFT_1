# CODSOFT_1
Task -

Number Guessing Game (C++)

This is a console-based number guessing game developed in C++ as part of my CodSoft Internship.

Description:

The program generates a random number between 1 and 100. The user sets the number of chances and tries to guess the correct number. After each guess, the program provides feedback to help the user make the next guess.

Features:

Random number generation using rand() and srand(time(0))

User-defined number of chances

Input validation through conditional checks

Feedback after each guess:

“Too high” if the guess is greater than the number

“Too low” if the guess is smaller

Success message if guessed correctly


Displays the correct number if the user runs out of chances


How to Run:

1. Compile the file using a C++ compiler:

g++ NumberGuessing.cpp -o NumberGuessing


2. Run the compiled file:

./NumberGuessing

3. Follow the on-screen instructions to play.

File Path:

/CODSOFT/NumberGuessing.cpp
