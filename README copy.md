# 04 Web APIs: Code Quiz

As you proceed in your career as a web developer, you will probably be asked to complete a coding assessment, which is typically a combination of multiple-choice questions and interactive challenges. Build a timed code quiz with multiple-choice questions. This app will run in the browser and feature dynamically updated HTML and CSS powered by your JavaScript code. It will also feature a clean and polished user interface and be responsive, ensuring that it adapts to multiple screen sizes.

## User Story

```
AS A coding bootcamp student
I WANT to take a timed quiz on JavaScript fundamentals that stores high scores
SO THAT I can gauge my progress compared to my peers
```

## Acceptance Criteria

```
GIVEN I am taking a code quiz
WHEN I click the start button
THEN a timer starts and I am presented with a question
WHEN I answer a question
THEN I am presented with another question
WHEN I answer a question incorrectly
THEN time is subtracted from the clock
WHEN all questions are answered or the timer reaches 0
THEN the game is over
WHEN the game is over
THEN I can save my initials and score
```

The following animation demonstrates the application functionality:

![code quiz](./Assets/04-web-apis-homework-demo.gif)

### Review

You are required to submit the following for review:

* The URL of the functional, deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.

Pseudo Code
// GIVEN I am taking a code quiz

    //The window will start with a <h1>coding quiz challenge<h1> 
        //a <p>explaining what the quiz is<p> 
        //a button that when you click begins the quiz html btn 

// WHEN I click the start button
    //create an on click event for the start button that will bring you to the first question <h2>first question<h2> 
        //four A. B. C. D. on click events with the answers to the question 
        //create a boolean value that is set to the button with the correct answer to be true 
            //the rest are if else the boolean === wrong and it will signal a string that states wrong 

// THEN a timer starts and I am presented with a question


// WHEN I answer a question
    //it will be either true or false 

// THEN I am presented with another question
    //This will also be true or false 

// WHEN I answer a question incorrectly
    // It is an if else statement which a string will appear stating wrong 

// THEN time is subtracted from the clock
    //look at timer activity 

// WHEN all questions are answered or the timer reaches 0
    // 
    
// THEN the game is over
// WHEN the game is over
// THEN I can save my initials and score
// WHEN you click view highscore 