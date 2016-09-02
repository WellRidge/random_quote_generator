# \#1 - Random Quote Generator
I've created a random quote generator to display quotations on the screen after a button on the page is clicked.

## Project Requirements

> * [x] Create an array of JavaScript objects to hold the data for the quotes.
> * [x] Name array `quotes`. The `quotes` array should be accessible in the global scope.


#### Each quote object should have the following properties:
> * [x] A `quote` property which contains a string: the text of the quote to display on the page
> * [x] A `source` property which contains a string identifying the creator of the quote. For example: "Mark Twain" or "Traditional Irish proverb"
> * [x] An optional `citation` property which contains a string identifying the publication the quote appears in. For example, "Famous Anonymous Jokes". If there is no known publication, then do not include this property on the object.
> * [x] An optional `year` property which contains a number identifying the date of the quote. For example, `1997`. If there is no known date, then do not include this property on the object.


#### Create a function named `getRandomQuote` which:
> * [x] selects a random quote object from the quotes array
> * [x] returns the randomly selected quote object


#### Create a function named `printQuote` which follows these rules:
> * [x] `printQuote` calls the `getRandomQuote` function and stores the returned quote object in a variable
> * [x] `printQuote` constructs a string using the different properties of the quote object using the following HTML template: 
```javascript
 <p class="quote"> [quote here] </p>
 <p class="source"> [source here] 
 <span class="citation"> [citation here] 
 </span> <span class="year"> [year here] </span> </p>
```
> * [x] `printQuote` doesn't add a \<span class="citation"> for a missing citation or a \<span class="year"> if the year property is missing
  * [x] `printQuote` displays the final HTML string to the page. You can use the following JS snippet to accomplish that: `document.getElementById('quote-box').innerHTML`

-----------
#### - Make sure you add code comments to document how your functions work
#### - Use [JSHint](http://jshint.com/) to analyze your JavaScript and identify any errors or code-style problems.
#### - Make sure your program is free of syntax errors. You can monitor any errors by looking at the Developer Tools console in your browser.
#### - Before you submit your project for review, make sure you can check off all of the items on the [Student Project Submission Checklist](http://treehouse-techdegree.s3.amazonaws.com/Student-Project-Submission-Checklist.pdf). The checklist is designed to help you make sure you’ve met the grading requirements and that your project is complete and ready to be submitted!
-----------
> **NOTE:** A good practice is to check your project for cross **browser compatibility**. Making sure that it looks and functions correctly in multiple (at least three) browsers is an important part of being a top-notch developer. If you want, leave a comment to the project reviewer about which browser(s) the project was checked to ensure they are seeing things as you have designed them.
Some browser options:
  * Google Chrome
  * Mozilla Firefox
  * Internet Explorer/Edge
  * Safari

## _Extra Credit_
To get an "exceeds" rating, you can expand on the project in the following ways:
* [x] __Add more properties to the quote object. For example, a `tags` property could include a list of "tags" like -- "humor", "business", "politics" -- to categorize each quote.__
* [x] __Randomly change the background color of the page, when the quote changes__
* [x] __Don't display a random quote more than once until ALL quotes from the array have been displayed.__
* [x] __Refresh the quote after a set amount of time. For example, every 30 seconds, make a new quote appear. You can use the [setInterval()](https://developer.mozilla.org/en-US/docs/Web/API/WindowTimers/setInterval) or [setTimeout()](https://developer.mozilla.org/en-US/docs/Web/API/WindowTimers/setTimeout) method to do this.__

## View Project

[Live Demo](https://wellridge.github.io/random_quote_generator/) of this project.
