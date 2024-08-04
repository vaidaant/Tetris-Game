# Tetris Game

## Overview
This project is a cross-platform Tetris game developed in C++ using the Raylib library. It features a scoring system, next block preview, sound effects, and smooth gameplay.

## Features
- **Scoring System**: Players earn points based on the number of lines cleared.
- **Next Block Preview**: Displays the next block to help players strategize.
- **Core Mechanics**: Includes block movement, rotation, collision detection, and line clearing.
- **Sound Effects**: Enhances the gaming experience with sound effects for clearing lines, rotating blocks, and background music.

## Files and Directories

- **.vscode/**: Contains Visual Studio Code settings for the project.
- **Font/**: Directory containing fonts used in the game.
- **lib/**: Directory containing the Raylib library files.
- **Sounds/**: Directory containing the sound effects and background music.
- **src/**: Contains the source code files.
  - **block.cpp**: Implements the block class.
  - **block.h**: Header file for the block class.
  - **blocks.cpp**: Manages the blocks in the game.
  - **colors.cpp**: Implements color functions.
  - **colors.h**: Header file for color functions.
  - **game.cpp**: Implements the main game logic.
  - **game.h**: Header file for the game logic.
  - **grid.cpp**: Manages the game grid.
  - **grid.h**: Header file for the game grid.
  - **main.cpp**: Entry point for the application.
  - **position.cpp**: Implements position-related functions.
  - **position.h**: Header file for position-related functions.
- **.gitattributes**: Specifies Git attributes.
- **.gitignore**: Specifies files to be ignored by Git.
- **Makefile**: Contains the build instructions for the project.
- **README.md**: This file.

## Installation

1. **Clone the Repository**
   ```sh
   git clone https://github.com/yourusername/tetris-game.git
   cd tetris-game
2. **Install Dependencies**
Ensure you have the Raylib library installed. You can download it from the official Raylib website.

3. **Build the Project**
   ```sh
   make
## Usage
**Running the Game**
Run the game executable generated in the build step:
    ```sh
    ./tetris
## Development
### Prerequisites
- C++ Compiler (e.g., g++)
- Raylib library

### Building the Project
Use the provided Makefile to build the project. Simply run:
```sh
make

## Customizing
You can customize various aspects of the game by modifying the source files in the src/ directory. For example, you can change the sound effects by replacing the .mp3 files in the Sounds/ directory.

## Contributions
Contributions are welcome! Please fork this repository and submit a pull request for any improvements or bug fixes.
