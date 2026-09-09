🎮 Hangman Game

A simple text-based Hangman Game built using Python 3.

In this game, a random word is selected from a list of 5 predefined words. Some letters of the word are hidden, and the player has to guess the missing letters one by one.

📌 Project Goal

The goal of this project is to create a simple console-based Hangman game while practicing basic Python programming concepts.

✨ Features

- 🎲 Random word selection
- 📝 5 predefined words
- 🔤 Some letters are hidden randomly
- 🎯 Player guesses one letter at a time
- ❌ Maximum 6 wrong guesses
- 🔁 Prevents repeated guesses
- ✅ Displays correct guesses
- 🏆 Shows a winning message
- 💀 Shows the correct word when the player loses
- 💻 Runs in the Python 3 console

🛠️ Technologies Used

- Python 3
- "random" module

🧠 Python Concepts Used

This project uses basic Python concepts:

- Lists
- Strings
- "random"
- "while" loop
- "for" loop
- "if-else"
- "input()"
- "append()"
- String joining
- Basic validation

🎮 How the Game Works

1. The program contains a list of 5 predefined words.
2. A word is randomly selected using "random.choice()".
3. Some letters of the word are hidden.
4. The player enters one letter at a time.
5. If the letter exists in the word, it is revealed.
6. If the letter is incorrect, the wrong-guess count increases.
7. The player gets a maximum of 6 wrong guesses.
8. The player wins when all hidden letters are revealed.

▶️ How to Run

Make sure Python 3 is installed.

Run the following command:

python3 hangman.py

On Windows, you can also use:

py -3 hangman.py

The project can also be run using Pydroid 3 on Android.

📂 Project Structure

hangman-game/
│
├── hangman.py
├── README.md
└── .gitignore

🖥️ Example

================================
         HANGMAN GAME
================================

Guess the missing letters!
You have 6 wrong guesses.

Word: p _ o _ r _ m m _ n _

Enter a letter: g

Correct guess!

Word: p _ o g r _ m m _ n g

🚀 Future Improvements

Some possible improvements for future versions:

- Add more words
- Add difficulty levels
- Add Hangman graphics
- Add score system
- Add replay option
- Create a graphical user interface

👨‍💻 Author

Akshat Saini

BCA Student | Python Learner
