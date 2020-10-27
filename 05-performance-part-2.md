# Performance 2
* Optimazing codes by writing efficient functions using react wisely and etting into some code splitting
* Progressive web app: making web applications as close to native mobile apps as possible

## Code Optimatation
* Only load what's neede:
  * Code splitting
  * Tree shaking
    * https://developers.google.com/web/fundamentals/performance/optimizing-javascript/tree-shaking/
* Avoid blocking main thread
* Avoid memory leaks
* Avoid multiple re-rendering

#### Webpage Performance Profiling using Chrome DevTools
1. Get Started With Analyzing Runtime Performance
    * https://developers.google.com/web/tools/chrome-devtools/evaluate-performance
2. Optimize Website Speed With Chrome DevTools
    * https://developers.google.com/web/tools/chrome-devtools/speed/get-started
3. Analyze Runtime Performance
    * https://developers.google.com/web/tools/chrome-devtools/rendering-tools
4. Performance Analysis Reference
    * https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/reference
5. Timeline Event Reference
    * https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/performance-reference
6. Speed Up JavaScript Execution
    * https://developers.google.com/web/tools/chrome-devtools/rendering-tools/js-execution

#### Webpage Performance Test
* https://www.webpagetest.org/

## Code Splitting in React
To send down a minimally functional page compsed of just HTML, JavaScript and CSS that we need for the current page. ***Lazy loading*** means just loading them after your page becomes interactive so that the user can feel like the app is fast
* https://reactjs.org/docs/code-splitting.html
* https://create-react-app.dev/docs/code-splitting
* https://www.geeksforgeeks.org/code-splitting-in-react
* https://hackernoon.com/effective-code-splitting-in-react-a-practical-guide-2195359d5d49

#### Using React Loadable for Code Splitting by Components and Routes:
* https://css-tricks.com/using-react-loadable-for-code-splitting-by-components-and-routes

#### Component-based splitting
* https://jamie.build/react-loadable.html
* react-loadable package: https://www.npmjs.com/package/react-loadable

#### React.lazy
* https://web.dev/code-splitting-suspense
* https://reactjs.org/docs/code-splitting.html#reactlazy
* https://loadable-components.com/docs/loadable-vs-react-lazy
* https://reactjs.org/docs/concurrent-mode-suspense.html

## React Performance Optimizations
#### Profiling Components with the Chrome Performance Tab
* Append ***?react_perf*** to your local server URL (e.g. localhost:3000/***?react_perf***) and visit that URL in a browse
* https://reactjs.org/docs/optimizing-performance.html#profiling-components-with-the-chrome-performance-tab
<img src="https://reactjs.org/static/64d522b74fb585f1abada9801f85fa9d/1ac66/react-perf-chrome-timeline.png">

#### Profiling Components with the DevTools Profiler
* React Developer Tools: https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=en
* react-devtools: https://www.npmjs.com/package/react-devtools

#### React setState is asynchronous
* https://medium.com/@wereHamster/beware-react-setstate-is-asynchronous-ce87ef1a9cf3
* https://vasanthk.gitbooks.io/react-bits/content/patterns/19.async-nature-of-setState.html

#### Stateless Component vs Pure Component
* https://medium.com/groww-engineering/stateless-component-vs-pure-component-d2af88a1200b

#### Why Did You Render
to notify you about avoidable re-renders
* https://www.npmjs.com/package/@welldone-software/why-did-you-render
