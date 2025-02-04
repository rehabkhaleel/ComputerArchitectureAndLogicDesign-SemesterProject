# Chance - Text-Based Adventure Game (MIPS Assembly)

## Project Description

"Chance" is a text-based adventure game developed using MIPS assembly language, which offers a unique gaming experience using low-level programming. Players interact with the game through simple text-based commands, making decisions that affect the game's outcome. This project aims to explore the use of MIPS assembly for interactive entertainment, focusing on the efficiency of game logic while providing an engaging adventure. Players will face quests, challenges, and random events in a world where each decision leads to different outcomes.

The game features:
- Interactive gameplay with decision points.
- Command-based user interaction.
- Quests and challenges that impact the storyline.
- MIPS assembly language optimized for performance.

## Technologies Used
- **MIPS Assembly Language**: Main programming language used for game development.
- **MARS (MIPS Assembler and Runtime Simulator)**: Tool used for compiling and running MIPS assembly code.

## Game Modules
- **Main Module**: Orchestrates the game flow and coordinates between other modules.
- **Input Module**: Handles user input and processes commands.
- **Output Module**: Displays game information and descriptions to the user.
- **Game State Module**: Maintains the game’s internal state.
- **Quest Module**: Manages quests, challenges, and decision points.
- **Location Module**: Tracks the player's position within the game world.
- **Character Module**: Defines player and NPC characters.
- **Event Module**: Triggers events and scripted sequences.
- **Utility Module**: Provides common utility functions used throughout the game.

## Project Setup

To run this game, you'll need the following:

### Prerequisites
- **MARS (MIPS Assembler and Runtime Simulator)**: Download and install MARS from [here](http://courses.missouristate.edu/kenvollmar/mars/).
- **Bitmap Display Tool**: For visualization, the Bitmap Display tool must be connected to MARS and configured with the following settings:
  - Unit width in pixels: 1
  - Unit height in pixels: 1
  - Display width in pixels: 1024
  - Display height in pixels: 1024
  - Base address for display: 0x10040000

### Running the Game
1. Download the project files.
2. Open the **MainProgram.asm** file in MARS.
3. Configure the Bitmap Display tool as described above.
4. Assemble and run the program using MARS.

### Game Instructions
- The game is controlled by entering commands in uppercase within brackets. For example, type `[A]` to make a decision in the game.
- Your choices determine your fate, with some paths leading to "hope" and others to "death."
- The game features random events, so each playthrough offers a different experience.

## Features
- **Interactive Storylines**: Navigate through quests and challenges with dynamic outcomes based on user decisions.
- **MIPS Assembly Implementation**: The game showcases the power and potential of assembly language for game development.
- **Minimalist, Text-Based Interface**: Focuses on the narrative and gameplay without complex graphical elements.
