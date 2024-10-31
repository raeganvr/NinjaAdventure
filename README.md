# Animated Path Adventure by Raegan Van Raamsdonk

Animated Path Adventure is a high school project designed to challenge players with strategic timing and pathfinding. Developed in JavaScript, the game requires players to navigate through levels filled with animated enemy characters who move along set paths. Players must avoid these enemies and reach the end of each level safely. Each level presents increasing difficulty, with more complex enemy paths and challenging layouts.

![Image](https://github.com/user-attachments/assets/placeholder-image.png)

## How It's Made
**Tech used:** JavaScript, HTML, CSS

Animated Path Adventure is built using JavaScript, HTML, and CSS. The game leverages simple JavaScript functions to control enemy movements, using a series of timed animations to create dynamic paths for the enemies. Each enemy moves along a specific track, changing direction at obstacles, which provides a visually engaging challenge for the player.

The level designs are created as grid-based arrays, allowing for easy customization of layouts and enemy behaviors. Each enemy’s movement is handled by a dedicated function that controls its path and reverses direction upon reaching the end. This setup allows for modular and flexible levels, with each element easily adjustable to increase or decrease difficulty.

The game’s logic is organized to ensure smooth animations and prevent overlap or glitches, with careful attention to timing and collision detection. By utilizing CSS classes for directional changes, the enemies appear to turn seamlessly when reversing their path, enhancing the visual flow of the game.

## Features
- Multiple levels with increasing difficulty.
- Animated enemies that follow defined paths and change direction upon reaching obstacles.
- Grid-based design, making levels easily customizable.

## Lessons Learned

Working on Animated Path Adventure taught me a lot about organizing code for game functionality and refining timing in animations. Implementing the grid-based system and seeing the levels come to life was a rewarding experience, and it deepened my understanding of JavaScript’s capabilities in handling game logic. One of my favorite moments was successfully implementing the enemy movements, especially when they changed direction at the right points, making the gameplay both challenging and satisfying.

This project strengthened my skills in JavaScript and introduced me to practical applications of HTML and CSS. It’s a great reminder that even simple game concepts can involve a lot of technical detail and problem-solving, and I look forward to taking these skills further in future projects.

## Getting Started

### Prerequisites
To run Animated Path Adventure, you need:
- A modern web browser (e.g., Chrome, Firefox, Edge).

### Running the Game

1. **Download the repository** or clone it with:
   ```bash
   git clone https://github.com/raeganvr/AnimatedPathAdventure.git
2. Open index.html in your browser to start the game.