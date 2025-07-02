# Basic-Hang-Man
Basic Hang-Man in English, created on python as choice for class project

Random was imported and used to randomely select a word from word list for user to guess.

User has 7 attempts to guess a letter of the mystery word (will show up as dashes for eacj letter of the word):
- Each failed attempt adds a body part to the hangman
- Each successful guess simply reveals where that letter appears in the word by replacing the dashed line where it belongs with   the letter.
- The user can attempt to guess the full word:
      -if user wins they will get a congratulations message
      -if they fail, they will get a failure notification and the game will resume with guesses
      -if word guess does not match the mystery word length, user will be shown an error message letting them know that the            length must match, and a note to try again
-Once user hits the 7th attempt and the hangman body is complete, user will be shown a Game Over message alongside what the mystery word was.
