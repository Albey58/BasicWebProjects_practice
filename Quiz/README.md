# Quiz Game Project

A simple, interactive, and responsive web-based Quiz Game built with HTML, CSS, and vanilla JavaScript. This project features multiple-choice questions, real-time score tracking, and a progress bar to enhance user experience.

---

## Features

* **Dynamic Question Rendering:** Questions and answers are dynamically injected into the DOM from a JavaScript object.
* **Responsive Design:** Optimized for both desktop and mobile devices using CSS Media Queries.
* **Real-time Feedback:** Instantly highlights correct and incorrect answers upon selection.
* **Score Tracking:** Calculates and displays your score both during the quiz and on the final results screen.
* **Progress Visualization:** A smooth progress bar indicates how far you are through the quiz.
* **Custom Result Messages:** Provides personalized feedback based on your final percentage score.

---

## Project Structure

The project consists of three main files:

| File | Description |
| :--- | :--- |
| `index.html` | Defines the structure of the start, quiz, and result screens. |
| `styles.css` | Handles the visual styling, animations, and responsive layout. |
| `script.js` | Contains the quiz logic, state management, and DOM manipulation. |

---

## How to Use

1.  **Start the Quiz:** Click the **"Start Quiz"** button on the landing page.
2.  **Select Answers:** Click on one of the four options provided for each question.
    * **Green:** Indicates the correct answer.
    * **Red:** Indicates your incorrect selection.
3.  **Automatic Progression:** After a 1-second delay, the game automatically moves to the next question.
4.  **View Results:** Once all questions are answered, the final screen displays your total score.
5.  **Restart:** Use the **"Restart Quiz"** button to try again.

---

## Technical Highlights

* **DOM Manipulation:** Uses standard JavaScript methods to manage screen transitions and dynamic button generation.
* **Dataset API:** Utilizes `element.dataset` to store answer data directly on buttons.
* **Event Handling:** Employs event listeners for user interactions with an optimization check to prevent double-clicking.
