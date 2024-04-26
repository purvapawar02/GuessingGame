# GuessingGame
I have implement a word-guessing game with the help of HTML, CSS, and JavaScr
Here, i have also provided a hint key & accept only a single letter as an input for each time to guess the correct word. If it is correct, then that letter will fill in that specific blank space, otherwise, the guessing will be continued, accordingly.
Created the Game project using Html tags,  like <div>, <h1> for the heading, <p> to display the word and the hint, and HTML input tag for guessed input letters with corresponding classes and IDs.
Add also create a stylesheet to make it look good using classes and elements that will define the padding, margin, font sizes to text, alignments, colors, etc to the specific elements.
In JavaScript, first, create an array of words to choose from for the quiz.
Then select a random word to display from the list by selecting a random index using JavaScript Math.random() method.
Push the guessed input in the guessedList array using array.push() and update the letter in displayWord at its every occurrence using a loop.
Every time check if the letter is already guessed show an alert “You have already guessed that letter”.
Display “You have guessed the word correctly” on alert when all letters have been guessed.
