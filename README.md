# JSON_quiz

A simple Beyonce trivia quiz!!!!!

**Link to project:** https://alia-json-quiz.netlify.com/

![alt tag](quiz.png)

## How It's Made:

**Tech used:** HTML5, CSS3, ES6, Fetch API, localStorage, array methods

Using **ES6**, I created a simple Beyonce trivia quiz application with clean code. The question/answer bank were saved in a **JSON** file, and pulled using the **fetch API**. The quiz has multiple views: a home page, a scoreboard, and the actual quiz questions. Makes use of **clean UI**, **semantic HTML5**, and **CSS3** for an efficient user experience. The high scores are saved in **localStorage** and 5 are displayed at a time on the scoreboard. The latest high scores are always shown, using the **sort() method to sort them in descending order** and the **splice() method** to cut off scores as new high scores are made. 

## Optimizations

If I were to make changes in this application, I would definitely store highest score/scoreboard information on the server instead of using localStorage. Though localStorage was efficient, considering this was a front-end project, business logic is generally best executed on the server so that nobody can cheat using the console.

I also did this same project with one added optimization, which was retrieving my questions and answers from the Open Trivia DB, check it out here: https://github.com/aliaabdulahi/openTriviaAPI_quiz

## Lessons Learned:

I learned a very simple and clean way to use the sort() method in a real-world application.

## Examples:
Take a look at these couple examples of vanilla JavaScript efficiency that I have in my own portfolio:

**Check out this same quiz with the Open Trivia Database API:** https://github.com/aliaabdulahi/openTriviaAPI_quiz

**Object-Oriented Library Assister:**  https://github.com/aliaabdulahi/OOP-Library-Assister

**:** 
