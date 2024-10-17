
# Car Racing Game

This project is a simple car racing game developed in C++ using basic console functionality. The game allows the player to control a car and avoid obstacles while moving through a track.

## Project File

- `PragCarGame.cpp`: The main C++ file that contains the implementation of the car racing game.

## Features

1. **Player Control**:
   - The player controls a car, which can move left or right.
   - The goal is to avoid obstacles coming towards the car.

2. **Obstacles**:
   - Randomly generated obstacles appear on the track.
   - The player must steer the car to avoid hitting these obstacles.

3. **Score**:
   - The game keeps track of the player's score, which increases as the player avoids obstacles.

## How to Compile and Run

### Prerequisites:
- You need a C++ compiler (e.g., `g++`) installed on your system.
- If you don't have it, you can install `g++` by following [this guide](https://gcc.gnu.org/).

### Steps:
1. **Compile the Code**:
   - Open a terminal or command prompt and navigate to the folder where the `PragCarGame.cpp` file is stored.
   - Run the following command to compile the file:
     ```bash
     g++ PragCarGame.cpp -o CarGame
     ```

2. **Run the Program**:
   - After compiling, run the game with the following command:
     ```bash
     ./CarGame
     ```

3. **Gameplay**:
   - Use the arrow keys or specified control keys to steer the car.
   - Avoid hitting the obstacles, and your score will keep increasing as you play.

## Future Improvements

Some potential improvements for this project:
- **Graphics Enhancement**: Implement graphical rendering using a library such as SDL or SFML for better visual effects.
- **Difficulty Levels**: Add multiple difficulty levels where obstacles speed up as the player progresses.
- **Score Saving**: Implement a high-score saving system to track the best scores across sessions.

## License

This project is open for educational purposes. Feel free to modify and enhance it as needed.
