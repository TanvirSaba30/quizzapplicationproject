# QuizBloom — Interactive Quiz App

QuizBloom is a beautiful and interactive quiz application designed to make learning fun and engaging. It allows users to play quizzes across multiple categories, track their performance, and create their own quizzes.

## Features

* **User Authentication UI**

  * Sign in
  * Create an account
  * Demo mode for running the application without Firebase

* **Multiple Quiz Categories**

  * Science
  * History
  * Geography
  * Math
  * Literature
  * Pop Culture

* **Different Difficulty Levels**

  * Easy
  * Medium
  * Hard

*  **Timed Questions**

  * Countdown timer for each question
  * Visual timer indicator

*  **Quiz Progress & Scoring**

  * Live score tracking
  * Question progress bar
  * Correct and incorrect answer feedback
  * Final score percentage
  * Average response time

*  **Performance Statistics**

  * Quizzes played
  * Correct answers
  * Best score

*  **Quiz Creator**

  * Create custom quizzes
  * Add multiple questions
  * Add answer options
  * Select the correct answer
  * Choose category and difficulty
  * Save and publish custom quizzes

*  **Interactive UI**

  * Responsive design
  * Animated interface
  * Confetti celebration on quiz completion
  * Modern pastel-themed design

##  Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript**
* **Local Storage**
* **Firebase** *(optional — for real authentication and cloud data)*

The current project is primarily contained in a single `index.html` file, including the HTML structure, CSS styling, and JavaScript functionality.

##  Project Structure

```text
QuizBloom/
│
├── index.html
└── README.md
```

##  Getting Started

### Run Locally

No build tools or package installation are required.

1. Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/quizbloom.git
```

2. Open the project folder.

3. Open `index.html` in your browser.

That's it! 

## 🌐Deployment

QuizBloom can be deployed as a static website using platforms such as:

* Netlify
* Vercel
* GitHub Pages

Since the application is contained in an HTML file, no backend server is required for the current demo mode.

## Firebase Setup

QuizBloom includes Firebase configuration support for authentication and Firestore.

The Firebase configuration is currently represented by placeholder values in the project.

To enable Firebase functionality:

1. Create a project in Firebase.
2. Add a Web App to your Firebase project.
3. Enable **Email/Password Authentication**.
4. Create a **Cloud Firestore** database.
5. Replace the placeholder Firebase configuration in `index.html` with your project's configuration.

>  Do not commit private credentials, service-account keys, or other sensitive secrets to your repository.

## Demo Mode

QuizBloom can run without a Firebase project.

When Firebase configuration has not been provided, the application uses **demo mode** and stores relevant user/stat information locally in the browser.

This makes it possible to test and demonstrate the application without setting up a backend.

##  How to Use

1. Open QuizBloom.
2. Sign in or create an account.
3. Choose a quiz from the available quiz library.
4. Answer each question before the timer runs out.
5. View your score and performance after completing the quiz.
6. Return to the dashboard to try another quiz.
7. Use **Create Quiz** to build your own quiz.

##  Current Status

**Version:** 1.0

QuizBloom is currently a front-end interactive quiz application with demo-mode functionality and optional Firebase integration.



## Author

**Tanvir Saba**



---


