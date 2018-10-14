# Drunky Clicky

This is a React.js app. Users, if they are behaving themselves, ought to click on each image card only once. Yet, the image cards automatically shuffle after each click, making it more difficult for the user to recall which cards they have not yet clicked. Twelve cards shuffle. An image can only be clicked once. Only one user can win (because only one user is playing at a time). Only one drunk in a thousand won't get dizzy from playing this game.

## How it works

- Users begin the game by clicking on a picture of some random drunk for whatever reason
- React will shuffle the image cards using an NPM package (Shuffle-Array). After each click, the logic will check to ensure that the user hasn't already selected an image
- If this occurs, the game should end.
- However, if the user has correctly selected an image only once after every shuffle, their scores should increase on the counter
- The app should update your highest score and reset scores, when the game ends

## Technologies

- React JS
