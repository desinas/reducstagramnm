# Learn Redux

A simple React + Redux implementation. These lessons built an application like Instagram.

## Running

First `npm install` to grab all the necessary dependencies. 

Then run `npm start` and open <localhost:7770> in your browser.

## Production Build

Run ` npm run-script build ` to create a distro folder and a bundle.js file.

## Summary of Redux

 - In Redux there is one big store that holds all of the app state `const defaultState = {  }` and update that with actions in file actionCreators.js where every action is a function that returns the type and the payload.
 - Cannot use async functions in the reducers of Redux, only pure functions. If needed to use async another package called redux-saga needed.
