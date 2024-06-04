# Sujiko Solver

This project is a Sujiko puzzle solver implemented in Java using the Swing framework for its graphical user interface. It was developed as part of a programming assignment at the Eindhoven University of Technology in November 2023.

## About Sujiko
Sujiko is a number puzzle where players are tasked with filling a grid of numbers such that the sum of the numbers in each subset equals a target number. This project automates the solving of such puzzles, providing both a backend algorithm for solving and a frontend for user interaction.

## Features
- **Interactive GUI:** Built with Java Swing for an intuitive user experience.
- **Efficient Solving Algorithm:** Implements logic to quickly and accurately solve Sujiko puzzles.
- **Custom Input:** Allows users to input custom puzzles for solving.
- **Visualization:** Displays the solving process in real-time.

## Usage
1. Launch the application using the steps in the Installation section.
2. Use the graphical interface to input the puzzle details:
   - Enter the grid size.
   - Input the target sums for each subset.
   - Fill in any known numbers.
3. Click "Solve" to view the solution.
4. Optionally, reset or modify the puzzle to test other configurations.

## Project Structure
- **src/**: Contains the source code.
  - **gui/**: Code for the graphical user interface.
  - **logic/**: Core logic and algorithms for solving Sujiko puzzles.
- **bin/**: Compiled Java classes.
- **README.md**: Project documentation.

## Technologies Used
- **Java**: Programming language.
- **Swing**: For the graphical user interface.
- **JUnit**: For testing.
