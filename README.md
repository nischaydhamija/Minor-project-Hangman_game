# Minor-project-Hangman_game
# 🕹️ Hangman Game

A simple command-line **Hangman game** implemented in **Python**. The game randomly selects a word from a list and lets the player guess it letter by letter. It visually tracks the player's progress using stages from a text file.

## 🎮 How to Play

1. The game randomly selects a word from the `words.txt` file.
2. The player guesses letters one by one.
3. If the guessed letter is in the word, it is revealed in the correct positions.
4. If the guessed letter is not in the word, a part of the hangman is drawn from `stages.txt`.
5. The player has a limited number of tries (6 by default).
6. The game ends when:
   - The player correctly guesses the word, or
   - The player runs out of tries

##  Files
- `hangman.py` – Main Python script to run the game  
- `words.txt` – A text file containing a list of words  
- `stages.txt` – A text file containing the hangman stages, separated by `###`  

##  Requirements
- Python 3.x
## ⚙️ Setup Instructions

1. **Clone the repository** or download the project files:
   ```bash
   git clone https://github.com/yourusername/hangman-game.git
   cd hangman-game
