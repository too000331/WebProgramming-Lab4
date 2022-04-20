# Lab 4 - Quiz app

## Story

Imagine, you're a developer at Sunny Entertainment GK, Tokyo. Ni hao. The company is struggling to find customers in Tokyo, so the marketing department proposes to launch a proof-of-concept app for running quizzes. The marketing campaign starts soon and you have to develop the app itself.

The good part is that there is a Quiz API that can be consumed by your application to fetch data about the quizzes.

## Task

1. Pick a frontend framework;
2. Create a web app that has the following functions:
  - it shows a landing page with different quizzes;
  - the user can pick a quiz and play it;
  - after the game has ended, the user can see their score.

3. The app should have attractive UI;
4. Consume [Quiz API](https://pure-caverns-82881.herokuapp.com) to fetch data from backend server.

## Special conditions

### React students

You have to use React as frontend library. Additionally, your app should be a multi-page app.

### Others

You have no restrictions on using third-party packages. However, your app should be a multi-page app.

## Grading

### React students
  Points:
  - attractive & responsive UI app - `7` points:
    - viewing a list of quizzes
    - viewing a single quiz
    - creating a user (and storing its ID somewhere)
    - playing a quiz for a user
    - submitting the responses out of the list (multiple choice)
    - showing the total score

  You can get `+1` point if the user can create a quiz of fixed number of questions -- additional `+1` if the number of questions is variable. You can get `+1` point for proper data validation.
  You can get `+1` point if the app includes some background music player / sound effects / visual effects (with condition that on URL change the music continues to play).

### Others

  Points:
  - basic app - `9` points:
    - viewing a list of quizzes
    - viewing a single quiz
    - creating a user (and storing its ID somewhere)
    - playing a quiz for a user
    - submitting the responses out of the list (multiple choice)
    - showing the total score
  - attractive & responsive UI - `+1` point.

  You can get `+1` point if the user can create a quiz of fixed number of questions -- additional `+1` if the number of questions is variable.
  You can get `+1` point if the app includes some background music player/ sound effects / visual effects (with condition that on URL change the music continues to play). You can get `+1` point if the app implements some other feature.

## Hints

- If you know a frontend framework - use it!
- If you don't know, use Vue/React or, better, Nuxt.js/Next.js (why?).
- Use a CSS library for UI part. You can give a try to Bulma, UIKit, Milligram or Tachyons. (Why not Bootstrap?)
- Use a high-level library to make HTTP requests e.g. axios.
- To track & keep progress in the app, you can use state managers provided by the framework e.g. Redux or Vuex.
- Use Postman to test the Quiz API **before** implementing the app itself -- create quizzes, create users, submit responses and so on.
- Keep it simple, commit often, improve gradually.
