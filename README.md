# README for Higher Lower Game

## Overview
This Python script is an interactive Higher Lower game where the player must guess which of two options has more followers. It's based on popular social media personalities, offering an engaging way for players to test their knowledge and intuition about popular figures.

## Features
- **Random Account Selection**: Chooses two random accounts from a provided dataset for comparison.
- **Account Formatting**: Displays the names, descriptions, and countries of the chosen accounts in an easy-to-read format.
- **Guess Evaluation**: The player's guess is evaluated, and they are informed if they're correct or not.
- **Scoring System**: Players earn points for each correct guess and the game continues until a wrong guess is made.

## How to Play
1. Run the script to start the game.
2. The game will display two accounts (A and B) with their descriptions and countries.
3. Guess which account has more followers by typing 'A' or 'B'.
4. The game informs you if your guess is correct and updates your score.
5. Continue guessing as long as you're correct. The game ends with your first wrong guess.

## Functions
- `get_random_account()`: Retrieves a random account's data from the dataset.
- `format_data(account)`: Formats the account data into a readable string.
- `check_answer(guess, a_followers, b_followers)`: Checks the player's guess against the follower counts.
- `game()`: The main game loop that orchestrates the gameplay.

## Dependencies
- `random`: For random account selection.
- `art`: Provides `logo` and `vs` for display enhancement.
- `game_data`: A module containing data about various social media accounts.

## How to Run
Ensure Python is installed on your system.

The `game_data` module is also present in your project, containing a `data` list of social media account information.

## Note
This game is purely for entertainment and educational purposes. It offers a fun way to explore social media influence and popularity.

---

Have fun playing and testing your social media savvy!