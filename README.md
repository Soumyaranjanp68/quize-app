# Quiz App

This project is a quiz app built using React. It allows users to take quizzes on various topics and provides instant feedback on their answers.

## Installation

1. Clone the repository: `git clone https://github.com/your-username/quiz-app.git`
2. Navigate to the project directory: `cd quiz-app`
3. Install dependencies: `npm install`

## Usage

1. Start the development server: `npm start`
2. Open your browser and visit `http://localhost:3000` to view the app.

## Features

- Multiple-choice questions with options.
- Random selection of questions for each quiz attempt.
- Instant feedback on correct and incorrect answers.
- Progress tracking and score calculation.
- Timer for time-based quizzes.
- Responsive design for mobile and desktop.

## Technologies Used

- React
- React Hooks
- CSS
- JSON data for questions

## Folder Structure

├── public
│ ├── index.html
│ └── ...
├── src
│ ├── components
│ │ ├── Quiz.js
│ │ └── ...
│ ├── data
│ │ ├── quizData.json
│ │ └── ...
│ ├── App.js
│ ├── index.js
│ └── ...
├── package.json
├── README.md
└── ...


## Customizing Quizzes

You can customize the quiz questions by modifying the `quizData.json` file inside the `src/data` directory. Each quiz question is represented as a JSON object with the following structure:

```json
{
  "question": "What is the capital of France?",
  "options": ["Paris", "London", "Berlin", "Rome"],
  "answer": "Paris"
}


