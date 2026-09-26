# React Quiz

A quiz application built with **React** to practice managing complex state with the `useReducer` Hook.

## Demo

https://fatemeh-abed.github.io/react-quiz/

## Features

* Fetch and display quiz questions
* Multiple-choice questions
* Score calculation
* Progress tracking
* Countdown timer
* High score tracking
* Restart the quiz
* Loading and error states
* Responsive UI

## Tech Stack

* React
* JavaScript
* `useReducer`
* `useEffect`
* CSS
* JSON Server for local development
* GitHub Pages for deployment

## What I Practiced

The main goal of this project was to practice **`useReducer`** for managing complex application state.

The quiz state includes:

* Current question
* Selected answer
* Score
* Quiz status
* Timer
* High score

Instead of managing these states with multiple `useState` calls, the application uses a reducer to handle state transitions through actions such as:

```js
start
newAnswer
nextQuestion
finish
restart
tick
```

This makes the state logic more centralized and easier to manage as the application grows.

## Local API

The project originally uses JSON Server for local development.

```bash
npm run server
```

The API runs at:

```text
http://localhost:8000
```

For the deployed version, quiz data is served as a static JSON file so the application does not depend on a local server.

## Deployment

The project is deployed using **GitHub Pages**.

To create a production build:

```bash
npm run build
```

To deploy:

```bash
npm run deploy
```
