
------------------------
Feed Reader Testing
------------------------

In this project you are given a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included Jasmine and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where you come in.

--------------------------
Start:
--------------------------
Project basic files:
1- index.html.
 a file where display result of each specs.

2- app.js
 java script code [allFeeds] array,laodFeed function and some DOM manipulation.

3- feedreader.js
 This is the spec file that Jasmine will read and contains all of the tests that will be run against your application.
 We're placing all of our tests within the $() function,
 since some of these tests may require DOM elements. We want to ensure they don't run until the DOM is ready.
--------------------------
Jasmin:
--------------------------

  is a behavior-driven development framework for testing JavaScript code. It does not depend on any other JavaScript frameworks. It does not require a DOM. And it has a clean, obvious syntax so that you can easily write tests. This guide is running against Jasmine version 2.0.0.
-------------------------  
How to write test?
-------------------------
1- Suites: describe Your Tests

A test suite begins with a call to the global Jasmine function describe with two parameters: a string and a function. The string is a name or title for a spec suite - usually what is being tested. The function is a block of code that implements the suite.

2-Specs

Specs are defined by calling the global Jasmine function it, which, like describe takes a string and a function. The string is the title of the spec and the function is the spec, or test. A spec contains one or more expectations that test the state of the code. An expectation in Jasmine is an assertion that is either true or false. A spec with all true expectations is a passing spec. A spec with one or more false expectations is a failing spec.

3-It's Just Functions

Since describe and it blocks are functions, they can contain any executable code necessary to implement the test. JavaScript scoping rules apply, so variables declared in a describe are available to any it block inside the suite.

4-Expectations

Expectations are built with the function expect which takes a value, called the actual. It is chained with a Matcher function, which takes the expected value.

For more information:
https://jasmine.github.io/2.0/introduction.html .
 

