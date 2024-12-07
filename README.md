# Guess the Superhero Game

## Description

The **Guess the Superhero** game is a fun, interactive puzzle game where players guess the name of a superhero based on an incomplete puzzle image. This game dynamically fetches superhero images and data from the [Superhero API](https://akabab.github.io/superhero-api/), and challenges players to identify superheroes with limited clues. The puzzle becomes more complete as players progress.

## Features

- **Interactive Puzzle**: Users solve a jigsaw puzzle of superhero images.
- **Dynamic Levels**: Fetch superhero data dynamically from the API.
- **Guessing Game**: Players have 3 attempts to guess the superhero name.
- **Responsive Design**: The game adapts to various screen sizes (mobile-friendly).
- **Settings & Themes**: Toggle dark mode and adjust sound settings.
- **Scoring System**: Tracks correct and failed guesses using `localStorage`.

---

## Technologies Used

- **HTML**: For structuring the game UI.
- **CSS**: For styling and responsiveness.
- **JavaScript**: For interactivity and game logic.
- **Superhero API**: Provides superhero data (images, names, etc.).
- **Headbreaker.js**: Generates the jigsaw puzzle pieces dynamically.

---

## How to Run the Game

### Prerequisites

Ensure you have the following installed:
- A modern web browser (Chrome or Firefox).
- Internet connection (to fetch superhero data from the API).

### Steps to Play

1. Clone or download this repository to your local machine.
2. Open the `index.html` file in a browser.
3. The game starts with Level 1 by default. 
4. Guess the superhero name by typing it in the input field and submitting your answer.
5. Adjust sound settings or theme using the icons in the header.

---

## Game Rules

1. **Objective**: Guess the superhero name based on the incomplete puzzle image.
2. **Attempts**: You have 3 attempts per level.
3. **Progression**: If you guess correctly, you proceed to the next level.

---

## Directory Structure

```plaintext
.
├── index.html
├── play.html
├── play-completed.html        
├── styles/
│   └── styles.css     
├── js/
│   ├── main.js        
|   ├── completed.js
│   ├── heros.js       
├── sounds/
│   └── background-music.mp3  
├── images/
│   └── heros/         
├── README.md          

