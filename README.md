# Assembly: Endgame

Assembly: Endgame is a fun and engaging word-guessing game where players aim to guess a word within a limited number of attempts. Protect the programming world from the menace of Assembly by guessing the secret word correctly!

## Features

- **Interactive Gameplay:** Guess letters to uncover the hidden word.
- **Dynamic Feedback:** Visual indicators for correct and incorrect guesses.
- **Thematic Design:** Programming languages as the theme, with a fun farewell message for incorrect guesses.
- **Accessible and Responsive:** Designed for all screen sizes with accessibility considerations.
- **New Game Option:** Restart the game anytime with a new word.

## Technologies Used

- **React** for the UI framework.
- **CSS** for styling and animations.
- **Confetti** (via `react-confetti`) for celebratory effects on winning.
- **Utilities:** Custom utilities for word generation and farewell messages.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd assembly-endgame
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```
5. Open your browser and navigate to `http://localhost:3000` to play the game.

## Project Structure

```
assembly-endgame/
├── src/
│   ├── components/
│   │   └── App.js        # Main component
│   ├── styles/
│   │   └── App.css       # Styling for the app
│   ├── utils/
│   │   ├── languages.js  # Language-related data
│   │   └── utils.js      # Utility functions
│   └── index.js          # Entry point
├── public/
│   └── index.html        # HTML template
└── package.json          # Project dependencies and scripts
```

## Gameplay Instructions

1. The goal is to guess the secret word within 8 attempts.
2. Click on the letters from the on-screen keyboard to make guesses.
3. Correct guesses reveal letters in the word, while incorrect guesses reduce the remaining attempts.
4. If you guess all the letters correctly, you win! Otherwise, the game ends when you run out of attempts.

## Customization

- **Word List:** Add or modify the word list in `utils/utils.js`.
- **Programming Languages:** Update the language chips in `utils/languages.js`.
- **Styling:** Modify styles in `styles/App.css` to customize the design.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature description"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- Inspired by classic hangman games.
- Special thanks to the developers and open-source community for their tools and resources.

