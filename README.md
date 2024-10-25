# 🧠 Trivia Triumph: Interactive Quiz App

## 🎮 Inspiration
As a first-year computer science student, I wanted to create an engaging way to reinforce my learning while also having fun. I decided to develop a quiz app that not only tests knowledge across various topics but also incorporates an interactive user experience. After thorough research and planning, I built this app to challenge players and enhance their trivia skills. Below is the documentation of my journey.

## ⚙️ How It Works
This Interactive Quiz App is built using JavaScript, HTML, and CSS, featuring key elements that create a dynamic quiz experience:

1. **Game Structure**: The app fetches quiz questions from the Open Trivia Database API, ensuring a wide variety of trivia questions.

2. **User Interface**: The app presents questions and answer choices using a responsive design, allowing for an intuitive gameplay experience. The user can select answers with visual feedback indicating correct or incorrect choices.

3. **Progress Tracking**: The app keeps track of the player's progress through the quiz, displaying the current question number and the overall score.

4. **Local Storage**: Player scores are saved in local storage, allowing users to view high scores and track their performance over time.

5. **Dynamic Question Loading**: Questions are randomly selected, ensuring a unique experience each time the user plays.

## 🚀 Key Functions
- **fetchQuestions()**: Retrieves trivia questions from the Open Trivia Database and formats them for use in the app.
- **startGame()**: Initializes the game, resetting scores and loading the first question.
- **getNewQuestion()**: Displays a new question, updates the progress bar, and handles the selection of answers.
- **incrementScore()**: Updates the player's score when a correct answer is selected.
- **saveHighscore()**: Saves the player's score to local storage, enabling a high score leaderboard.

## 🛠️ Technical Aspects
The app is developed using:
- **JavaScript**: The primary language for game logic and functionality.
- **HTML/CSS**: Used for structuring and styling the user interface.
- **Open Trivia Database API**: A source for fetching diverse trivia questions.

