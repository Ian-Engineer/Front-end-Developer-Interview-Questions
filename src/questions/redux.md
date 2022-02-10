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
*** 
