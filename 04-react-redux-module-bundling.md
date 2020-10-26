# React + Redux + Webpack
Allow us to fix many things
* Writing code that is more maintainable
* Writing code that is more readable
* Writing code that creates less bugs
- State management: Redux
- Bundling: Webpack

## Frameworks and Libraries for Frontend
* Angular, Vue, React ([npm-trends](https://www.npmtrends.com/angular-vs-react-vs-vue))
  * Which tool is good for the job at hand? Each tool has its pros and conds

## React
#### Main Concepts
* https://reactjs.org/
* https://reactjs.org/docs/components-and-props.html
* https://reactjs.org/docs/state-and-lifecycle.html
* https://reactjs.org/docs/composition-vs-inheritance.html

#### React Virtual DOM
* https://programmingwithmosh.com/react/react-virtual-dom-explained/

#### React Ecosystem
* https://www.toptal.com/react/navigating-the-react-ecosystem
* https://itnext.io/react-ecosystem-guide-4a5f85d17623

#### React Error Boundaries
* https://reactjs.org/docs/error-boundaries.html
* https://reactjs.org/docs/react-component.html#componentdidcatch

#### Deploying Using Create React App
* https://create-react-app.dev/docs/deployment/#github-pages

## Redux
Redux is a library that makes state management easier
* https://react-redux.js.org/introduction/why-use-react-redux

<img src="https://blog.codecentric.de/files/2017/12/Bildschirmfoto-2017-12-01-um-08.53.32.png">

> "https://blog.codecentric.de/en/2017/12/developing-modern-offline-apps-reactjs-redux-electron-part-3-reactjs-redux-basics/"
>

#### Why Redux
1. Good for managing large state
2. Useful for sharing data between containers
3. Predictable state management using the 3 principles
    1. Single source of truth
        * One single massive state object
    2. State is read only
    3. Changes only using pure functions

<img src="https://miro.medium.com/max/700/1*OLdS7KqIA_4f1RHu0-YtsQ.jpeg">

> "https://medium.com/octopus-labs-london/replacing-redux-with-react-hooks-and-context-part-1-11b72ffdb533"
>
1. Action: is the only thing that should trigger a state change.
2. Reducer: specifies what part of the store will be affected by the action.
3. Store: holds all the application data in an object tree.
4. Component: has access to the store and can change the store by triggering an action.

* Flux and Redux Patterns
  * https://facebook.github.io/flux/docs/in-depth-overview
  * https://www.dotnetcurry.com/reactjs/1356/redux-pattern-tutorial

<img src="https://facebook.github.io/flux/img/overview/flux-simple-f8-diagram-1300w.png">

#### Redux Installation
* https://redux.js.org/introduction/installation

#### How to Use
* https://thoughtbot.com/blog/using-redux-with-react-hooks
* https://blog.bitsrc.io/using-react-redux-hooks-97654aff01e4

#### Redux Middleware
* redux-logger: https://www.npmjs.com/package/redux-logger
* redux-thunk: https://www.npmjs.com/package/redux-thunk
* chrome extension: https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd

## Popular Tools for React & Redux
***Adding any library adds extra weight and adds extra javascript that we need to deliver to the client. So make sure if you're adding any of these things that you have a justifiable reason that actually improves the value of your product***
* [React Router](https://reactrouter.com): Declarative Routing for React.js
* [Ramda](https://ramdajs.com): A practical functional library for JavaScript programmers
* [Lodash](https://lodash.com): A JavaScript utility library delivering consistency, modularity, performance, & extras
* [glamorous](https://glamorous.rocks): Maintainable CSS with React
* [styled components](https://styled-components.com/): Lets you write actual CSS in your JavaScript
* [Gatsby](https://www.gatsbyjs.com/): React-based open source framework for creating websites and apps
* [Next.js](https://nextjs.org/): Enables functionality such as server-side rendering and generating static websites for React based web applications
* [Material-UI](https://material-ui.com/): A popular React UI framework
* [Reselect](https://github.com/reduxjs/reselect): Selector library for Redux
* [Redux-Saga](https://redux-saga.js.org/): Middleware library that is designed to make handling side effects in your redux app nice and simple
* [Immutable.JS](https://immutable-js.github.io/immutable-js/): Designed to provide immutability in a performant manner in an effort to overcome the limitations of immutability with JavaScript

## Code Structure
* https://redux.js.org/faq/code-structure
* https://www.pluralsight.com/guides/how-to-organize-your-react-+-redux-codebase

## Webpack
Webpack is a static module bundler for modern JavaScript applications
#### Popular bundlers([npm-trends](https://www.npmtrends.com/parcel-vs-rollup-vs-webpack))
* [Webpack](https://webpack.js.org/): bunch of configuration, for a large project
* [Parcel](https://parceljs.org/): zero configuration, for a small or private project
* [Rollup.js](https://rollupjs.org/guide/en/): rolling out your own NPM packages

#### [Core Concepts](https://webpack.js.org/concepts/)
* Entry
* Output
* Loaders
* Plugins
* Mode
* Browser Compatibility

#### Easy Configuration
* https://www.valentinog.com/blog/webpack/
* Using Create App: https://createapp.dev/webpack
* webpack.config.js Guide: https://webpack.js.org/configuration/
