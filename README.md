# Rock Paper Scissors Game

A simple, interactive command-line Rock Paper Scissors game built with Python. Challenge the computer and test your luck!
##  Description

This is a classic Rock Paper Scissors game implementation in Python featuring an interactive command-line interface. Play unlimited rounds against a computer opponent that makes random choices. The game includes emoji representations for an engaging visual experience and validates all user inputs.
## ✨ Features

-  Interactive command-line gameplay
-  Emoji representations for choices (🪨 📃 ✂️)
-  Input validation and error handling
-  Replay functionality for multiple rounds
-  Random computer opponent
-  Clear win/lose/draw feedback

## 🎮 Game Rules

- **Rock (🪨)** crushes **Scissors (✂️)**
- **Scissors (✂️)** cuts **Paper (📃)**
- **Paper (📃)** covers **Rock (🪨)**
- Same choices result in a **Draw**

## 🚀 Getting Started

### Prerequisites

- Python 3.x installed on your system
- No external dependencies required

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/rock-paper-scissors.git
```

2. Navigate to the project directory:
```bash
cd rock-paper-scissors
```

3. Run the game:
```bash
python rock_paper_scissors.py
```

## 🎯 How to Play

1. **Make your choice** when prompted:
   - Press `r` for Rock 🪨
   - Press `p` for Paper 📃
   - Press `s` for Scissors ✂️

2. **View the results**: The game displays both your choice and the computer's choice with emojis

3. **See who won**: The game announces whether you won, lost, or drew

4. **Play again**: Choose to continue (`y`) or exit (`n`)

## 📸 Example Gameplay

```
Rock, Paper, Scissor? (r/p/s) :r
You chose 🪨
Computer chose ✂️
You win!
Do you want to play again? (y/n) :y

Rock, Paper, Scissor? (r/p/s) :s
You chose ✂️
Computer chose 🪨
you lose!
Do you want to play again? (y/n) :n
```

## 🏗️ Code Structure

```python
├── get_user_choice()      # Handles and validates user input
├── display_choices()      # Shows player and computer choices
├── determine_winner()     # Implements game logic
└── play_game()           # Main game loop with replay functionality
```

## 🛠️ Technical Details

**Constants:**
- `ROCK`, `PAPER`, `SCISSOR`: Choice identifiers
- `emojis`: Dictionary mapping choices to emoji representations
- `choices`: Tuple of valid choice options

**Game Flow:**
1. User input collection and validation
2. Random computer choice generation
3. Choice display with emojis
4. Winner determination based on game rules
5. Replay prompt

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 👤 Author

**Sakshi Vishwakarma**

- GitHub: [@developerSakshi365](https://github.com/developerSakshi365)

⭐ If you found this project helpful, please give it a star!

**Happy Gaming! 🎉**