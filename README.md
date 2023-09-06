# Quizzed App

Welcome to Quizzed, a simple web application that allows users to take quizzes on various topics. This project provides a user-friendly interface for taking quizzes and viewing quiz results.

![Welcome-To-Quizzed](https://github.com/Muth80/quizzed/assets/117746069/2d2b25cc-7253-4c6d-9f64-4755b1c06885)

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Adding Your Own Questions](#adding-your-own-questions)
- [Contributing](#contributing)
- [Support](#support)

## Features

- **Topic Selection:** Users can choose from a variety of quiz topics, such as IQ, Physics, Engineering, and more.
- **Interactive Quizzes:** Users can take quizzes with interactive multiple-choice questions.
- **Immediate Feedback:** Users receive immediate feedback on whether their answers are correct or not.
- **Score Tracking:** The application tracks the user's score and displays it at the end of the quiz.
- **Responsive Design:** The user interface is responsive and works well on both desktop and mobile devices.

## Getting Started

To get started with the Quizzed App, follow these steps:

1. Clone this repository to your local machine using `git clone`.

2. Open the `index.html` file in a web browser.

3. Check out the app here: https://quizzed-six.vercel.app/


![Welcome-To-Quizzed (1)](https://github.com/Muth80/quizzed/assets/117746069/89664856-1318-4de4-a58d-3e96389ec987)



## Usage

1. Upon opening the Quizzed App, you'll see the main page with a list of available quiz topics.

2. Click on a quiz topic of your choice, such as "IQ Test," "Physics," or "Engineering."

3. You will be presented with a series of interactive multiple-choice questions related to the selected topic.

4. Click on your chosen answer for each question.

5. After answering all the questions, you will receive your quiz score, displayed as a percentage.

6. You can restart the quiz or choose a different topic from the main page.

## Adding Your Own Questions

You can easily extend the Quizzed App by adding your own questions. Follow these steps to add questions:

1. Open the `index.html` file in a code editor.

2. Scroll down to the JavaScript section, where you'll find the `questions` object. This object contains quiz questions organized by topic.

3. To add a new topic, add a new property to the `questions` object with the topic name as the key and an array of questions as the value. For example:
   ```javascript
   "MyTopic": [
       {
           "question": "What is your question?",
           "options": ["Option 1", "Option 2", "Option 3", "Option 4"],
           "correctAnswer": "Option 2"
       },
       // Add more questions here
   ]
   ```

4. Make sure to follow the existing structure with the "question," "options," and "correctAnswer" fields.

5. Save the `index.html` file and refresh your browser to see the new topic and questions.

## Contributing

Contributions to this project are welcome. If you have ideas for improvements or new features, feel free to open an issue or submit a pull request.

## Support

Follow my account. https://github.com/Muth80

---

Enjoy using the Quizzed App for your educational and entertainment purposes! If you encounter any issues or have suggestions, please don't hesitate to [report them](https://github.com/Muth80/quizzed-app/issues). Thank you for using and contributing to this project.

