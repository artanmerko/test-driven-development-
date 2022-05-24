# test-driven-development introduction
# Test-Driven Development - TDD Introduction with JavaScript

## About 
Test-Driven Development (TDD) is a proven prevent bugs and improve the quality of your code - and it's fun! Learn the fundamentals of JavaScript testing in this beginner's tutorial. Test Driven Development, or TDD for short, is a big deal in the modern development landscape. This is a concept that we introduced way back in our Fundamentals section with our JavaScript Exercises. The main idea is simply that you start working on your code by writing automated tests before writing the code that is being tested. There are tons of benefits to working like this, all of which will be discussed in the resources below.

🔗 Resources
- Jest https://jestjs.io/
- Cypress https://www.cypress.io/
- Fun TDD Introduction with JavaScript https://www.youtube.com/watch?v=Jv2uxzhPFl4
- Software Testing Practices and Strategies https://www.devision.com/software-testing-practices-strategies/

![tdd-life-circle-1](https://user-images.githubusercontent.com/97398977/170129998-a41b9635-aba8-4a87-a3e3-cd0af8d17b70.png)

### How to start
 Install Build tool vite
 ```
 npm init @vitejs/app
 ```
 Install testing framework Jest
 ```
 npm install jest --save-dev
 ```
 Create file js/stack.test.js for testing
 
package.json 
```
"test": "jest"
```
We can add `--watchAll` to rerun the test anytime it changes and `--verbose` to add some extra output to the terminal
 ``
