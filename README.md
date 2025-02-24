# Project-Computer-Science
Project Computer Science Assignment  

## Overview
The **Quiz App** is an interactive Android application that allows users to test their knowledge across various subjects through engaging quizzes. The app features a user-friendly interface, real-time scoring, and leaderboard rankings. It is designed to promote learning and make knowledge assessment fun and competitive.

## Features
- **User Authentication**: Secure sign-up and login using Firebase Authentication.
- **Quiz Categories**: Users can select from multiple categories like Science, Math, History, and General Knowledge.
- **Timed Questions**: Each question is time-limited to keep the game challenging.
- **Dynamic Question Bank**: Questions are fetched in real-time from Firebase Firestore.
- **Instant Feedback**: Correct answers are highlighted in green, incorrect ones in red.
- **Leaderboard System**: Tracks high scores and ranks users based on their performance.
- **User Profile Management**: Users can view and track their progress and scores.

## Technical Requirements
- **Android**: Compatible with Android devices running OS Nougat 7.1.0 or higher.
- **Firebase**: Utilizes Firebase for authentication, real-time database, and leaderboard management.
- **Programming Languages**: Java (Backend), XML (UI Design).
- **Development Environment**: Android Studio.

## Installation
To set up the app on your local machine, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Manish-Kumar-Vats/project-Computer-Science-Project.git
    ```
2. Open the project in Android Studio.
3. Sync the project with Gradle files.
4. Make sure to set up Firebase:
- Create a Firebase project in the Firebase console.
- Download the `google-services.json` file and place it in the `app/` directory.
5. Build the project in Android Studio and run it on an Android device or emulator.

## Usage
- **Register and Login**: Create an account or log in with existing credentials.
- **Select a Quiz Category**: Choose from different subjects available on the Home screen.
- **Answer Questions**: Read the question, choose an option, and submit the answer within the time limit.
- **View Results**: Check your score at the end of the quiz session.
- **Track Leaderboard Rankings**: See how you rank compared to other users.

## Contributing
Contributions to the Quiz App are welcome. Please consider the following steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.

## Acknowledgments
- Thanks to all the contributors who have helped with testing, feedback, and new ideas.
- Special thanks to [Google Firebase](https://firebase.google.com/) for providing the backend services used in this app.
