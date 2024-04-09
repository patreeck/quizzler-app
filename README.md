**Quizzer - True/False Quiz Application**

**Overview:**

Quizzer is a simple True/False quiz application built using Python and Tkinter GUI library. It presents a series of True or False questions fetched from an external API and allows users to answer them interactively.

**Technologies Used:**

**Python:** Programming language used for the backend logic and application development.

**Tkinter:** Python's standard GUI (Graphical User Interface) toolkit used for creating the interactive user interface.

**Open Trivia Database API:** External API used to fetch trivia questions for the quiz.

**Features:**

1. Fetches a set of True/False questions from the Open Trivia Database API.

2. Displays quiz questions one by one on a Tkinter canvas.

3. Allows users to answer each question by clicking True or False buttons.

4. Provides immediate feedback on user answers (green for correct, red for incorrect).
Tracks and displays the user's score throughout the quiz.

5. Shows a final score summary at the end of the quiz.




**Project Structure:**

**main.py:** Entry point of the application, initializes the quiz interface and starts the quiz loop.
**quiz_brain.py:** Implements the QuizBrain class to manage quiz logic and question handling.
**ui.py:** Defines the QuizInterface class responsible for creating and managing the Tkinter GUI.
**question_model.py:** Contains the Question class representing a single quiz question.
**data.py:** Retrieves and processes data from the Open Trivia Database API.


**Usage:**

Run main.py to start the Quizzer application.
Answer each True/False question by clicking the corresponding button.
Receive immediate feedback on your answers and track your score.
At the end of the quiz, view your final score summary.

<img width="122" alt="image" src="https://github.com/patreeck/quizzler-app/assets/163764755/a5061ace-3b9c-490e-b996-94ea8f10bb0f">
<img width="122" alt="image" src="https://github.com/patreeck/quizzler-app/assets/163764755/55b88456-734a-4357-b4b7-1c4c98b5905c">

