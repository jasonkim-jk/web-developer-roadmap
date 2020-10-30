# Testing
A method in software development where individual units of source code assets or programs are tested to see whether they work properly

<img src="https://miro.medium.com/max/638/0*74Xfdpuqz8gDMcVI">

> https://medium.com/@jylglim/enzyme-vs-react-testing-library-a-tdd-bdd-comparison-with-examples-7b9f0b380a48

* https://sathyalog.wordpress.com/2020/04/14/react-test-driven-development-tutorials/
* https://blog.gurock.com/unit-testing-tdd-bdd/

## Types of Tests
<img src="https://cdn-media-1.freecodecamp.org/images/1*aH_ifsVI0cI5P5Guu1X1CQ.jpeg">

> https://www.freecodecamp.org/news/unit-testing-services-endpoints-and-repositories-in-spring-boot-4b7d9dc2b772/

<img src="https://www.softwaretestingnews.co.uk/wp-content/uploads/2018/07/Screen-Shot-2018-07-04-at-10.35.26.png">

> https://www.1point21gws.com/insights/qualitytesting/adopting-the-test-pyramid-model-approach/

#### Unit Tests
* Most common and easiest to implement
* Tests individual functions or classes
* https://itnext.io/how-to-unit-test-in-react-72e911e2b8d

#### Integration Tests
* How different pieces of code work together
* https://www.toptal.com/react/react-testing-library-tutorial

#### Automation Tests
* Real life scenarios
* End-to-End: UI tests that are always running inside a browser or a browser like environment

## Testing Libraries
* https://www.npmtrends.com/chai-vs-jest-util-vs-mocha-vs-mocha-nightwatch-vs-jest-vs-jasmine
* https://medium.com/codeclan/testing-react-with-jest-and-enzyme-20505fec4675
* https://blog.bitsrc.io/7-react-testing-libraries-you-should-know-b20ca97422a4
* https://medium.com/welldone-software/an-overview-of-javascript-testing-7ce7298b9870

#### Libraries
* Jest: https://jestjs.io, https://github.com/facebook/jest
* Jasmine: https://jasmine.github.io/
* Mocha: https://mochajs.org/
* Chai: https://www.chaijs.com/
* Karma: https://karma-runner.github.io/
* Sinon.js: https://sinonjs.org/
* Enzyme: https://enzymejs.github.io/enzyme/
* TestCafe: https://devexpress.github.io/testcafe/
* Nightmare: http://www.nightmarejs.org/

## Setting Up Jest and Writing Test
* Jest cheat sheet: https://github.com/sapegin/jest-cheat-sheet
* Test Code: https://github.com/jasonkim-jk/exercise-projects/tree/main/jest-test

#### Asynchronous test
* https://jest-bot.github.io/jest/docs/tutorial-async.html
* https://jestjs.io/docs/en/asynchronous
* https://medium.com/@benjimorr/how-to-mock-asynchronous-methods-with-jest-38408434a6f4
* https://www.pluralsight.com/guides/test-asynchronous-code-jest

#### Mock and Spy
* https://jestjs.io/docs/en/mock-functions
* https://medium.com/swlh/javascript-testing-jest-spies-and-mocks-add0048ba345
* https://www.jstwister.com/post/unit-testing-beginners-guide-spying-fake-timers/


## Enzyme
Enzyme is a JavaScript Testing utility for React that makes it easier to test your React Components' output. You can also manipulate, traverse, and in some ways simulate runtime given the output.

#### Important Methods
###### Shallow(Most using), Mount, Render
* https://enzymejs.github.io/enzyme/docs/api/
* https://gist.github.com/fokusferit/e4558d384e4e9cab95d04e5f35d4f913
* https://medium.com/@Yohanna/difference-between-enzymes-rendering-methods-f82108f49084
* https://blog.usejournal.com/testing-with-jest-and-enzyme-in-react-part-4-shallow-vs-mount-in-enzyme-d60cad73f85c

## Snapshot Test
A typical snapshot test case renders a UI component, takes a snapshot, then compares it to a reference snapshot file stored alongside the test. The test will fail if the two snapshots do not match: either the change is unexpected, or the reference snapshot needs to be updated to the new version of the UI component.

<img src="https://miro.medium.com/max/700/1*EDPrWEKqMClrMO6zia570w.png">
<img src="https://miro.medium.com/max/700/1*PgpFYJCIwbUl_7c_EMprwQ.png">
> https://medium.com/@luisvieira_gmr/snapshot-testing-react-components-with-jest-3455d73932a4

* https://www.digitalocean.com/community/tutorials/how-to-write-snapshot-tests-for-react-components-with-jest
* https://jestjs.io/docs/en/snapshot-testing

## Jest Coverage Report
<img src="https://cdn-media-1.freecodecamp.org/images/1*8eP9WhWo1VrmS_kUg7LssA.png">

* https://www.freecodecamp.org/news/get-your-npm-package-covered-with-jest-and-codecov-9a4cb22b93f4/
* https://jestjs.io/docs/en/cli#--coverageboolean

## Testing React Component’s State
* https://www.reactnative.guide/7-testing/7.3-enzyme-testing.html
* https://enzymejs.github.io/enzyme/docs/api/ReactWrapper/state.html
* https://www.valentinog.com/blog/testing-react/

## Testing Connected Components
* https://www.robinwieruch.de/react-connected-component-test
* https://hacks.mozilla.org/2018/04/testing-strategies-for-react-and-redux/

## Testing Reducers
* https://www.digitalocean.com/community/tutorials/react-testing-redux-reducers
* https://redux.js.org/recipes/writing-tests
