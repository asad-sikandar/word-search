====================================================
            MINI GAME ARCADE PROJECT
====================================================

1. PROJECT OVERVIEW
----------------------------------------------------

This project is a console-based Mini Game Arcade
developed in C++ using Object Oriented Programming
(OOP) concepts.

The program contains multiple text-based games
which are selected randomly using polymorphism.

The games included in this project are:

1. Word Scramble
2. Word Search

The application also includes:
- Random game selection
- Difficulty management
- Performance report
- Score calculation
- Dynamic memory allocation
- User interaction system

----------------------------------------------------

2. OOP CONCEPTS USED
----------------------------------------------------

1. Classes and Objects
2. Inheritance
3. Polymorphism
4. Abstraction
5. Encapsulation
6. Virtual Functions
7. Dynamic Binding

----------------------------------------------------

3. GAME DESCRIPTIONS
----------------------------------------------------

A) WORD SCRAMBLE GAME
----------------------

The player is shown scrambled words.
The objective is to guess the correct word.

Example:
Scrambled Word: rayar
Correct Answer: array

Each correct answer increases the score.

----------------------------------------------------

B) WORD SEARCH GAME
----------------------

The player is shown a character grid.
Hidden words must be identified from the grid.

Example Hidden Words:
- STACK
- QUEUE
- GAME

The player enters words to find them.

----------------------------------------------------

4. HOW TO RUN THE PROGRAM
----------------------------------------------------

STEP 1:
Open any C++ compiler such as:

- Dev C++
- CodeBlocks
- Visual Studio
- VS Code
- Online GDB

STEP 2:
Create a new C++ file.

STEP 3:
Copy and paste the complete project code.

STEP 4:
Save the file with .cpp extension.

Example:
mini_game_arcade.cpp

STEP 5:
Compile and run the program.

----------------------------------------------------

5. CONTROLS
----------------------------------------------------

WORD SCRAMBLE:
- Type the correct word
- Press ENTER

WORD SEARCH:
- Enter hidden words
- Press ENTER

MAIN SYSTEM:
- Y = Play Again
- N = Exit Program

----------------------------------------------------

6. SETTINGS
----------------------------------------------------

Difficulty Levels:
- Easy
- Medium
- Hard

Difficulty automatically changes according to
player performance.

High score increases difficulty level.
Low score decreases difficulty level.

----------------------------------------------------

7. PERFORMANCE REPORT
----------------------------------------------------

At the end of the game session, the program
displays:

- Total Games Played
- Total Score
- Average Score

----------------------------------------------------

8. RANDOM GAME SELECTION
----------------------------------------------------

Games are selected randomly using:

rand() % number_of_games

This demonstrates polymorphism and dynamic
object creation.

----------------------------------------------------

9. FILE STRUCTURE
----------------------------------------------------

Main Components:

1. Game Class
   Base abstract class

2. WordScramble Class
   Derived game class

3. WordSearch Class
   Derived game class

4. PerformanceReport Class
   Handles score reporting

5. Main Function
   Controls overall game flow

----------------------------------------------------

10. REQUIREMENTS
----------------------------------------------------

Language:
- C++

Libraries Used:
- iostream
- string
- ctime
- cstdlib

----------------------------------------------------

11. AUTHORS
----------------------------------------------------

Developed By:
[Your Name Here]

Course:
Object Oriented Programming (OOP)

Project:
Mini Game Arcade

----------------------------------------------------

12. FUTURE IMPROVEMENTS
----------------------------------------------------

Possible future upgrades:

- Add Hangman Game
- Add Tic Tac Toe
- Add File Handling
- Add Leaderboard
- Add Timer
- Add Multiplayer Support
- Add GUI Interface

====================================================
            END OF README FILE
====================================================
