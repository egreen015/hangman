# hangman
Hangman Game - README

This is a simple Hangman game developed by Earl Green. The game is designed to test your knowledge of programming languages. Guess the programming language by selecting letters from the on-screen keyboard. Be careful! Each wrong guess brings you one step closer to losing the game.
How to Play

    Open the index.html file in a web browser.
    You will see a title that reads "Jon Ruth the Hangman" and an image representing the current state of the hangman.
    The word to be guessed is displayed as underscores (_) in the "Guess the Programming Language" section.
    Click on the letters in the on-screen keyboard to make a guess.
    If the letter is correct, it will appear in its corresponding position(s) in the word. If it is incorrect, the hangman image will progressively change, and the "Wrong Guesses" counter will increase.
    Keep guessing letters until you either guess the word correctly or make too many wrong guesses.
    If you win, a congratulatory message will be displayed. If you lose, a message showing the correct word will be displayed.

Customization

You can customize the game by modifying the following files:

    jr.css: This file contains the CSS styles for the game. You can change the appearance of the game elements by modifying the styles defined in this file.

css

.container2 {
  background-color: #deb887;
  /*background-image: url('hangmanbackground.jpg');*/
  background-size: cover;
  background-position: center;
  /* Add other styles as needed */
}

.text-center {
  color: #934CF5;
}

p {
  color: aliceblue;
}

#wordSpotlight {
  color: aliceblue;
}

.floatRight {
  color: aliceblue;
}

.btn {
  color: #934CF5;
}

    jr.js: This file contains the JavaScript code that runs the game. You can modify the programming languages in the programming_languages array to include your own set of words for guessing.

javascript

var programming_languages = [
  "python",
  "javascript",
  "mongodb",
  "json",
  "java",
  "html",
  "css",
  "c",
  "c sharp",
  "golang",
  "kotlin",
  "php",
  "sql",
  "ruby",
];

// Rest of the JavaScript code...

Technologies Used

The Hangman game was developed using the following technologies:

    HTML: Markup language used for structuring the game interface.
    CSS: Styling language used for designing the visual appearance of the game.
    JavaScript: Programming language used for implementing the game logic.

Credits

The Hangman game was developed by Earl Green. It is a personal project created for educational purposes.
License

This project is licensed under the MIT License. Feel free to modify and distribute it according to the terms of the license.
