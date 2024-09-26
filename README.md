# Project Management Quiz App

## Overview
This is a **Project Management Quiz App** built with **React**. The app presents users with 10 questions related to project management scenarios. Users select their level of agreement with each scenario (Strongly Disagree to Strongly Agree), and based on their responses, the app assigns them a project management role (Leader, Collaborator, Doer, Strategist, or Facilitator).

## Features
- **Quiz with 10 Questions**: Multiple choice quiz with 5 response options for each question.
- **Dynamic Role Calculation**: An algorithm assigns a role based on how the user's answers align with predefined role characteristics.
- **Responsive Design**: The app works on both mobile and desktop devices.
- **Progress Tracking**: Users can see their progress and navigate between questions.
- **Result Page**: Displays the assigned project management role with a description.
- **Share Functionality**: Allows users to share their result (optional).
- **Return Button**: Lets users return to the home page after completing the quiz.

## Technologies
- **React.js**
- **React Router** for page navigation.
- **Hooks or Redux** for state management.
- **CSS** for clean, professional UI and responsive design.

## Installation

1. Clone the repository:

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the development server:
    ```bash
    npm start
    ```

## Usage

1. Navigate to the home page and click the "Start" button to begin the quiz.
2. Answer 10 questions by selecting one of the 5 response options for each.
3. The app will calculate and display the user's project management role at the end.
4. Users can share their results using the provided share button or return to the home page.

## Algorithm
- Each role starts with a base score of 0.
- User responses are scored based on the difference between their answer (1-5) and the role's ideal answer for that question.
- The role with the lowest cumulative score is selected as the user's project management style.



## License
This project is licensed under the MIT License.
