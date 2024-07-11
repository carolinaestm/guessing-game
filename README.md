# guessing-game

This project is a simple C++ program developed for the CSCE 1030 - Computer Science I course at the University of North Texas. It is a console-based game where the user guesses a number between two randomly generated numbers. The game involves displaying these numbers, guessing, and changing them. The goal is to guess correctly and accumulate points.
  
## Authors

- Carolina Estrada (cme0145) - carolinaestrada@my.unt.edu
- Cody Smith (cjs0531) - codysmith13@my.unt.edu
- Taras Glushko (tmg0208) - tarasglushko@my.unt.edu
  
## Game Rules

1. The game begins by asking for the user's name and ensuring it is valid (only contains letters and spaces). The name is then formatted properly with appropriate capitalization and suffixes (Sr, Jr).

2. Two random numbers between 150 and 250 are generated, with the left number always being less than the right number.

3. The user is presented with a menu with the following options:

 1. Display Left Number: Displays the left number and reduces the points gained for a correct guess to 1.
 2. Display Right Number: Displays the right number and reduces the points gained for a correct guess to 1.
 3. Guess a Number in Between: The user guesses a number between the two numbers. Points are awarded or deducted based on whether the guess is correct and if any number was displayed.
 4. Change Numbers: Generates new random numbers and resets the displayed numbers. One point is deducted for this action.
 5. Exit: Ends the game and displays the total points.
4. The game loop continues until the user chooses to exit or runs out of points.
   
## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your_username/gpa-calculator.git
   cd gpa-calculator
