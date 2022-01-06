# cypress-cheatsheet
cheat sheet for cypress commands

# Cypress.io Cheat sheet
### ```Context and Hooks```
|function|what it does|
|---------|-----------|
|describe |group & label tests + manage context & hooks|
|it |label a test block|
|before |hook that runs before all tests in context/describe|
|after |hook that runs after all tests in context/describe|
|beforeEach| hook that runs before each tests in context/describe|
|afterEach| hook that runs after each tests in context/describe|

### ```.should & Common Chainers```
|function|what it does|
|---------|-----------|
|.should |command used for asserting tests. (docs)|
|"have.class" |check for class|
|"have.css" |check for CSS style|
|"be.visible" |check if visible. (docs)|
|"exist" |check if element exists|
|"have.length"| checks for number of matching elements|
|"have.value" |checks the value of input field|
|"be.checked" |checks for state of radio or checkbox|
|"contains" |checks value within opening and closing tags.|


### ```Utility Commands```
|function|what it does|
|---------|-----------|
|cy.log |log comment to command log|
|cy.fixture |yeilds fixture (docs)|
|.then( callback )| work with yeilded subject|
|.wait |wait a certain amount of ms (docs)|
|.pause |stop testing at certain point|
|.then( callback ) |work with yeilded subject|
|.screenshot |take a screenshot of state of DOM|
|.debug| print debug info to the console|



### ```Selection Commands```
|function|what it does|
|---------|-----------|
|cy.get| select based on HTML tag attrs|
|cy.contains |select based value within opening and closing tags|
|.first| select first matching element|
|.last |select last matching element|
|.next| select next matching element|
|.prev |select previous matching element|
|parents |select parent of element|
|.children| select child of element|
|.siblings |select sibling of element|
|.closest |find closest element|
|.find |find matching child element|




### ```Action Commands```
|function|what it does|
|---------|-----------|
|.click |click on an element|
|.dblclick| double click on an element|
|.rightclick |right click on an element|
|.type("foobar")| type "foobar" into an element|
|.clear |clear all text from an element|
|.check |check a checkbox or radio|
|.uncheck |uncheck a checkbox or radio|
|.focus |focus on an element|
|.blur |blur an element|
|.submit| submit a form.|
|.trigger(''click")| trigger any DOM event|
|.hover| hover over an element(docs)|
|.select |select option from a dropdown menu|

### ```Browser Commands```
|function|what it does|
|---------|-----------|
|cy.visit| visit url|
|cy.go("back")| click on browser's "back" button|
|cy.go("forward")| click on browser's "forward" button|
|cy.reload |refresh the page|
|cy.viewport |change window size|
|cy.url |yeilds current url|
|cy.window |yeilds current window object|
|cy.title |yeilds document.title object|
|.scrollIntoView |scroll element into view|
|.scrollTo| scroll to position in the window|
