# React/Redux Flashcard App

This is a flashcard application that not only allows students to create quizzes in the form of flashcards they can study, but the quizzes are also sorted by topic once it is created

## To Run

Run `npm install` to download the node_modules folder and then run `npm start` in the project root and the app will be available on port 3000.

## Routes

- `/new-topic` – form to create a new topic
- `/topics` – index of all topics
- `/topics/:topicId` – page for an individual topic
- `/new-quiz` – form to create a new quiz
- `/quizzes` – index of all quizzes
- `/quizzes/:quizId` – page for an individual quiz

## Technologies

* Javscript
* Node.js
* React
* React Router
* Redux

## Features

* Create Topics for Quizzes
* Create Quizzes
* Create Cards in the Quizzes to that have a question and answer to study

## To Test

1. Create topics
2. Create quizzes
3. Visit the page for an individual quiz and flip the cards over

## images

The main page will only show the navbar at the top of the screen. From there, the user can visit the following routes: `/topics`, `/quizzes`, and `/new-quiz`.

When the user creates a new topic, they can choose a custom name for it and select an icon that represents said topic. they will then be displayed on the `/topics` screen.

![topics](https://github.com/MasonBoom/React-Redux-Flashcards/blob/7563c4bcc514fdf6afcc940c83a49e31258b89ec/images/React%20App%20-%20Google%20Chrome%203_18_2022%207_36_41%20AM.png)

Next, the user can create a quiz for the topic they have made. If the user attempts to make a quiz without the topic or name, they will not be able to proceed.

![createquiz](https://github.com/MasonBoom/React-Redux-Flashcards/blob/7563c4bcc514fdf6afcc940c83a49e31258b89ec/images/React%20App%20-%20Google%20Chrome%203_18_2022%207_40_30%20AM.png)

The quizzes made by the user will then be displayed on the `/quizzes` screen

![quizzes](https://github.com/MasonBoom/React-Redux-Flashcards/blob/7563c4bcc514fdf6afcc940c83a49e31258b89ec/images/React%20App%20-%20Google%20Chrome%203_18_2022%207_41_00%20AM.png)

Once a user clicks on a quiz they want to study for, the cards for that quiz will appear on their screen, and they can flip the card by clicking on it.

![cards](https://github.com/MasonBoom/React-Redux-Flashcards/blob/7563c4bcc514fdf6afcc940c83a49e31258b89ec/images/React%20App%20-%20Google%20Chrome%203_18_2022%207_41_15%20AM.png)
