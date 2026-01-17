🎰 Python Slot Machine Game

A simple command-line slot machine game built using Python.
Players can deposit money, choose the number of lines to bet on, place bets, spin the slot machine, and win based on matching symbols across rows.

📌 Features

Deposit virtual money to start playing

Choose 1–3 betting lines

Place bets within a defined range

Randomized slot machine spins

Winnings calculated based on symbol values

Continuous gameplay until the player quits

🎮 How the Game Works

The slot machine has a 3×3 grid

Each column contains randomly selected symbols

A winning line occurs when all symbols in a row match

Each symbol has:

A frequency (how often it appears)

A value (how much it pays)

Symbols & Values

Symbol	Count	Value

A	2	5

B	4	4

C	6	3

D	8	2

🧠 Logic Overview

deposit() – Handles user deposit input

get_number_of_lines() – Selects number of betting lines

get_bet() – Bet amount per line

get_slot_machine_spin() – Generates randomized columns

print_slot_machine() – Displays the slot machine

check_winnings() – Calculates winnings

spin() – Runs one full game round

main() – Game loop controller

▶️ How to Run the Game
Prerequisites

Python 3.x installed

Steps

Clone the repository:

git clone https://github.com/your-username/slot-machine-game.git


Navigate to the project folder:

cd slot-machine-game


Run the program:

python slot_machine.py

🧪 Example Output

A | B | C

D | D | D

C | B | A


You won $6.

You won on lines: 2

🚀 Future Improvements (Optional Ideas)

Add diagonal winning lines

Implement jackpot system

Add GUI using Tkinter or Pygame

Save player balance between sessions

📄 License

This project is open-source and free to use for learning and personal projects.

👨‍💻 Author

Jayasurya R

Python Learning Project
