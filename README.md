# Feed Reader Testing

## Overview

<p>This is the fourth project for my Udacity frontend Nanodegree Program.</p>
<p>Udacity provided us with a web-based application that reads RSS feeds.</p>
<p>My task was completeing the unit testing using <a href="https://jasmine.github.io/">Jasmine framework</a>.</p>


## The Project Purpose?
<p>Letting us figure out how to write a number of tests against a pre-existing application.</p>

## How to Run the Application
This App does't need any setup, all you need is
* Clone the repository to your local machine or download the project
* Open the index.html file in your browser to see the test results
* If in the lower part of the page all dots are green assures that the required functionality works as expected and the tests ran successfully
* If in the lower part of the page one or more dots are red means that some tests failed

### The following functionality (in app.js file) is being tested
1. allFeeds variable has been defined and that it is not empty ('RSS Feeds' suite => 'are defined' spec).
2. Each feed in the allFeeds object has a defined URL and that the URL is not empty ('RSS Feeds' suite => 'has a URL' spec).
3. Each feed in the allFeeds object has a defined name and that the name is not empty ('RSS Feeds' suite => 'has a name' spec).
4. the menu element is hidden by default('The menu' suite => 'hidden by default' spec).
5. the menu changes visibility and it displays when the menu icon is clicked and it hides when the menu icon is clicked again ('The menu' suite => 'changes visibility' spec).
6. when the loadFeed  function is called and completes its work, there is at least a single .entry element within the .feed container ('Initial Entries' suite => 'there is at least a single .entry element within the .feed container' spec).
7. when a new feed is loaded by the loadFeed function that the content actually changes ('New Feed Selection' suite => 'the content actually changes when loadFeed invoke' spec).
