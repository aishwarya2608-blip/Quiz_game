# Python Quiz Game

This project is a **Quiz Game developed using Python** that presents questions to users, checks their answers, and keeps track of their scores throughout the quiz. The project is organized into four Python files: `question_model.py`, `data.py`, `main.py`, and `quiz_brain.py`. Each file has a specific responsibility, making the code structured, organized, and easy to understand.

## Project Files and Their Functionality

### 1. `question_model.py`
This file defines the `Question` class, which represents an individual quiz question. It stores the question text and its corresponding answer, allowing the questions and answers to be managed in a structured format.

### 2. `data.py`
This file contains the quiz data, including the questions and their corresponding answers, which are either `True` or `False`. This data serves as the question bank for the quiz.

### 3. `quiz_brain.py`
This file defines the `QuizBrain` class, which manages the main logic of the quiz. It contains several functions that control the quiz flow and track the user's progress.

- **Question and Score Management:** Keeps track of the current question and the user's score.
- **Checking for Remaining Questions:** Determines whether any questions are left in the question bank.
- **Displaying the Next Question:** Retrieves and displays the next question along with its question number.
- **Checking Answers:** Compares the user's answer with the correct answer, displays whether the answer is correct, reveals the correct answer when necessary, and updates the current score.

### 4. `main.py`
This file serves as the entry point of the project. It imports the `Question` class from `question_model.py`, the question data from `data.py`, and the `QuizBrain` class from `quiz_brain.py`.

It creates a question bank by converting the question data into `Question` objects and appending them to a list. It then initializes the quiz using the `QuizBrain` class and runs a `while` loop to display the next question as long as questions remain. Once all the questions have been answered, the program displays the final score and informs the user that the quiz has been completed.

## Key Features

- Interactive True/False quiz.
- Organized question and answer data.
- Object-oriented programming using classes and objects.
- Automatic question progression using a `while` loop.
- Real-time answer checking and score tracking.
- Feedback on answers, including the correct answer.
- Final score display upon quiz completion.

## Concepts Learned

This project demonstrates the practical application of Python concepts, including classes and objects, functions, lists, loops, conditional statements, modules, imports, and basic object-oriented programming.

## Conclusion

The Python Quiz Game is a beginner-friendly project that demonstrates how to build an interactive quiz application using modular code and object-oriented programming. It provides a practical understanding of how to organize data, manage program flow, validate answers, and track scores in Python.
