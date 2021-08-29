# code-quiz

## Description
This is a quiz developed to practice certain JavaScript features I am learning. For that reason I did not spend much time on styling, which is part of why it looks so ugly.

It includes nested arrays, functions to cycle through those arrays and check user input against those arrays, a timer, event listeners, quite a few selectors, and more. After taking the quiz, the user can enter their initials, which will be put into local storage along with their score, and then pulled from local storage and displayed.

The quiz questions on JavaScript are pulled from various web sources and should not be taken seriously, particularly the last question and the welcome text re: "Lord of the Code," which was written at the very start of this process, when I thought I would have the time to add some "Lord of the Rings"-inspired design elements to this quiz. How optimistic I was. Similarly, I hoped to develop a better scoreboard page, but time is short and I'm on to other projects.

![Gif demonstrating quiz in action](/assets/demo/code-quiz-demo.gif)

## Installation
Download the files and then view the code. 
- The web page was deployed via GitHub pages and is live here: https://alexdmacon.github.io/code-quiz/
- The GitHub repository is here: https://github.com/alexdmacon/code-quiz

## Usage
You will have 40 seconds to answer 5 multiple choice questions about javascript. You will lose 10 seconds for every wrong answer. Save your initials and score after successfully completing the quiz. Click "Yeah! Start the Clock" to start the quiz. Or click the button that says "No! I don't have what it takes!" if you're chicken.

## Credits
My in-house tutor provided invaluable input and helped clean up what was previously a buggy mess by walking me through this line by line.
Among the approximately 300 web pages and references I looked at, these were especially helpful, particularly the MDN documentation on the indexof() method, which saved me from my biggest headache:
//https://codingnepal.medium.com/create-a-quiz-app-with-timer-using-html-css-javascript-f460087a88a1
//https://stackoverflow.com/questions/45449106/how-to-make-a-ul-list-of-buttons-accessible/45491521
// https://www.codingnepalweb.com/quiz-app-with-timer-javascript/
// https://codepen.io/boopalan002/pen/yKZVGa
// https://www.w3schools.com/js/js_quiz.asp
// https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Iterators_and_Generators
// https://www.sitepoint.com/simple-javascript-quiz/
// https://michael-karen.medium.com/how-to-save-high-scores-in-local-storage-7860baca9d68
// https://www.w3schools.com/jsref/prop_style_display.asp
// https://stackoverflow.com/questions/60370557/how-can-you-deduct-10-seconds-from-a-running-timer-in-javascript
// https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/indexOf