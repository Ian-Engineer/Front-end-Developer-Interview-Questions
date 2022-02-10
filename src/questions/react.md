* Differentiate between Real DOM and Virtual DOM
*** Real DOM updates slow, expensive manipulation, memory waste. Virtual DOM updates faster, updates the element not DOM, easy manipulation, no memory waste.

* What is React?
*** React is a front end Javascript library, helps to build reusable UI components, develop complex and interactive web and mobile UI.

* React features?
*** Virtual DOM, server side rendering, uni-directional data flow

* Major advantages of React?
*** Increases applications performance, can be used in client side and server side, readability increases (JSX), easy to integrate with other framework, UI test writing is easier

* Limitations of React
*** Just a library not full blown framework, very large library takes time to understand, uses inline templating so it gets complex.

* What is JSX
*** Shorthand for javascript xml. Utilizes expressiveness of javascript while also using HTML syntax.

* How does the Virtual DOM work?
*** lightweight javascript object. A node tree that lists the elements, their attributes and content as Objects and their properties. Updates the tree in response to mutations in the data model.

* Why can't browsers read JSX?
*** can only read javascript, but jsx is not a regular javascript object. To let a browser read JSX files, it needs to be transformed using babel and then pass it into the browser.

* How different is React's ES6 syntax compared to ES5?
*** changed require to import, and export module to just export, if you use classes for react components you use extends react.component, 

* How is react different from Angular?
*** angular is client side rendering, uses a real dom, two way data binding, runtime debugging, created by Google.

* In react, everything is a component, explain.
** Components are the building blocks of react applications UI. Components split up the UI into small independent reusable pieces. Then renders each component.

* What is the purpose of render() in React
*** Returns a single react element, if more than one element is required, they must be enclosed in another element.

* Phases of a react component's lifecycle
*** Initial rendering (default values) --> updating phase (re rendering) --> unmounting phase (removed from DOM)

* Lifecycle methods of react components
*** componentWillMount() --> executed just before rendering takes place both on the client as well as server side
*** componentDidMount() --> executed on client side after the first render
*** componentWillReceiveProps() --> invoked as soon as the props are received fromt he parent class and before another render is called.
*** shouldComponentUpdate() --> returns true or false value based on certain conditions. if you want it to update return true, returns false by default.
*** componentWillUpdate() --> called just before rendering takes place in the DOM
*** componentDidUpdate() --> called immediately after rendering takes place
*** componentWillUnmount() --> called after the component is unmounted from the DOM.

* What is an event in React?
*** an action a user takes, they are triggered. like on click, on hover, key press.

* What are synthetic events in React?
*** objects which act as a cross-browser wrapper around the browser's native event.

* what do you understand by refs in React?
*** ref is the short hand for reference. Helps store a reference to a particular react element or component. 

* List some use cases of when you should use Refs
*** need to manage focus, select text or media playback, to trigger imperative animations, integrate with third-party DOM libraries

* How do you modularize code in react?
*** by using the export and import properties.

* How are forms created in React?
*** similar to HTML forms. State is contained in the state property of the component and is updated via setState().

* Controlled vs uncontrolled components?
*** controlled: do not maintain their own state, data is controlled by parent, take in values from props and notify changes through callbacks.
*** uncontrolled: maintain their own state, data controlled by DOM, refs are used to get their current values.

* What are higher order components?
*** an advanced way of reusing the component logic. Custom components that wrap another component within it.

* What can you do with higher order components?
*** code reuse, state manipulation, render high jacking, props manipulation

* What are pure components?
*** simplest and fastest components which can be written. They replace any component which on has a render().

* What is significane of keys in React?
*** keys are used for identifying unique virtual dom elements. Helps react optimize the rendering by recycling all the existing elements in the DOM.

* What are the major problems with MVC framework?
*** MVC Framework - model, view, controller
*** DOM manipulation was very expensive
*** applications were slow and inefficient
*** there was huge memory waste
*** circular dependencies

* Explain Flux
*** an architectural pattern, enforces the uni-directional data flow. Controls data and enables communication between multiple components using a central store which has authority for all data.

* What is Redux?
*** Predictable state container for javascript apps. Used for the entire applications state management. Easy to test and can run in different environments with consistent behavior.

* Principles that redux follows?
*** single source of truth: state of the entire function is in an object/state tree. Single state tree makes it easier to keep track of changes over time and debug.
*** state is read only: only way to change the state is to trigger an action. An action is a plain JS object describing the change.
*** changes are made with pure functions: pure functions are those whose return value depends solely on the values of their arguments.

* Single source of truth?
*** entire applications state is stored at one place. Since state is stored in one place, you cannot have differing values for it within the app.

* List down the components of redux
*** Action - object that describes what happened
*** reducer - place to determine how the state will change
*** store - state/object tree of the entire application is saved in the store
*** view - displays the data provided by the store

* How does data flow through redux?
*** an event is triggered in a component --> action --> dispatch describing how state will change --> modify state in store --> displays new state

* How are actions defined in Redux?
*** actions must have a type property that indicates the type of action. a string constant. Create actions with action creators

* Explain the role of reducer?
*** pure functions specify how the applications state changes in response to an action. Take in previous state and action, then returns a new state.

* Significance of Store in redux?
*** a store is an object which can hold the applications state and provide a few helper methods to access the state. The entire state is stored in a single store.
*** Redux is simple and predictable. Can pass middleware to the store to handle the processing of data. 

* How is redux different from flux?
*** Flux: store contains state and change logic, multiple stores, stores disconnected and flat, has singleton dispatcher, react components subscribe to store, state is mutable.
*** Redux: store and change logic are separate. One store. Hierarchical reducers. No concept of dispatcher. Container components utilize connect. State is immutable.

* Advantages of redux?
*** predictability of outcome: always one source of truth.
*** maintainability: strict structure
*** server-side rendering: provides better user experience, optimizes performance.
*** Developer-tools: can track everything going on in the application in real time.
*** community and ecosystem: huge community behind it.
*** ease of testing: redux's code is mostly small functions. Makes the code testable and independent.
*** organization: precise about how code should be organized. Makes the code consistent.

* what is react router?
*** routing library built on top of react. adds new screens and flows to the app. Keeps the url in sync with data that's being displayed.

* Why is switch keyword used in React Router v4?
*** used when you want to display only a single route to be rendered amongst the several defined routes.

* Why need a router in react?
*** used to define multiple routes. user is redirected to a route.

* advantages of react router?
*** can be viewed as a single component - BrowserRouter

* How is react router different from conventional routing?
*** conventional: each page is a new file. HTTP request sent to server. User actually navigates across different pages for each view.
*** react: Only single HTML page is involved. Only history attribute is changed. User is not navigating to different pages.















