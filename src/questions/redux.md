https://www.fullstack.cafe/blog/top-26-react-redux-interview-questions-to-brush-up-2018

* what is flux?
*** replacement for mvc pattern. User takes an action -- dispatch changes store -- view is updated

* redux dev tools?
*** live editing time travel environment with reloading, action replay and customizable UI. There is an extension in chrome and firefox if you don't want to bother installing it into your project.

* what is redux?
*** a state container for javascript based on flux design pattern.

* how to add multiple middlewares to redux?
*** use applyMiddleware - pass each piece of middlware as a new argument. I've used thunk

* how to set initial state in redux?
*** pass initial state as second argument to createStore

* how to structure redux top level directories?
*** Components - stateless. Containers - stateful. Actions - action creators. Reducers. Store - store initialization

* what are redux selectors?
*** functions that take redux state as an argument and return some data. This is how you get data from the state.

* what are reducers?
*** takes the previous state and an action and returns the next state

* what are the core principles of redux?
*** Single source of truth. State is read only. changes are made with pure functions. A pure function always returns the same result if the same arguments are passed.

* What is redux thunk?
*** middleware allows you to write action creators that return a function instead of an action.

* What are features of redux devtools?
*** lets you inspect every state and action payload. Go back in time by cancelling actions. If you change reducer code, each staged action will be re-evaluated. If reducers throw, you will see which action caused it. Can persist debug sessions across page reloads.

* what is redux-saga
*** a library that aims to make side effects in react/redux applications easier and better.

* difference between react context and react redux
*** context is great for passing down data to deeply nexted components. Redux uses context internally so its safer, and redux is more powerful, large number of features.

* how to use connect from react redux?
*** use mapStateToProps() --> connect the above props to your container

* 







