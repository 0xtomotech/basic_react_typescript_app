
# Hangman Game

![License](https://img.shields.io/badge/license-MIT-green)
![React Version](https://img.shields.io/badge/react-17.0.2-blue.svg)
![TypeScript](https://img.shields.io/badge/typescript-4.1.2-blue.svg)

This project is a web-based **Hangman game** implemented using React and TypeScript. Players try to guess a word by suggesting letters within a limited number of guesses.

## Table of Contents
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Components](#components)
- [Contributing](#contributing)
- [License](#license)

## Project Structure
| File               | Description                                           |
|--------------------|-------------------------------------------------------|
| `App.tsx`          | The main React component orchestrating the game logic |
| `HangmanDrawing.tsx` | Manages the visual representation of the hangman     |
| `HangmanWord.tsx`  | Displays the word to be guessed                      |
| `Keyboard.tsx`     | Renders a virtual keyboard for letter input          |
| `wordList.json`    | Contains the list of possible words to guess         |
| `Keyboard.module.css` | CSS module for styling the virtual keyboard        |

## Installation

Ensure you have Node.js installed on your machine to run this project.

```bash
# Clone the repository
git clone <repository-url>

# Navigate to the project directory
cd <project-name>

# Install dependencies
npm install

# Start the development server
npm start
```

## Usage

After starting the project, navigate to `http://localhost:3000` to start playing. Guess the word by clicking on the letters in the virtual keyboard. Correct and incorrect guesses are tracked visually.

## Components

### `App`
Manages the game's state and handles logic for guessing letters, determining wins, or losses.

### `HangmanDrawing`
Dynamically renders the hangman drawing as incorrect guesses accumulate.

### `HangmanWord`
Controls the display of the word being guessed, revealing letters as they are correctly identified.

### `Keyboard`
Manages user input from the virtual keyboard and delegates letter guesses to the game logic.

<details>
  <summary>## Contributing</summary>
  Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

  1. Fork the Project
  2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
  3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
  4. Push to the Branch (`git push origin feature/AmazingFeature`)
  5. Open a Pull Request
</details>