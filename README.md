# Simon Game

This JavaScript file implements the logic for a Simon game, a classic memory game where players must repeat a sequence of colors and tones generated by the game. The game starts with a sequence of colors being displayed and played, and the player must then repeat the sequence by clicking on the colored buttons. If the player succeeds, the game advances to the next level, adding another color to the sequence. If the player makes a mistake, the game ends.

## Functionality

- **Starting the Game**: Press any key to start the game. The level will be displayed, and the game will begin.
- **Playing the Game**: Click on the colored buttons to repeat the sequence generated by the game.
- **Winning**: If the player successfully repeats the entire sequence, the game advances to the next level.
- **Losing**: If the player makes a mistake, the game ends, and the player must restart by pressing any key.

## Variables

- **buttonColours**: An array containing the colors available in the game.
- **gamePattern**: An array containing the sequence of colors generated by the game.
- **userClickedPattern**: An array containing the sequence of colors clicked by the player.
- **started**: A boolean indicating whether the game has started.
- **level**: The current level of the game.

## Functions

- **checkAnswer(currentLevel)**: Checks if the player's sequence matches the game's sequence up to the current level.
- **nextSequence()**: Generates the next color in the game's sequence and displays it to the player.
- **animatePress(currentColor)**: Animates the button press by adding and removing a CSS class.
- **playSound(name)**: Plays the sound associated with a given color.
- **startOver()**: Resets the game variables to their initial state.

## Usage

1. Include the Simon game JavaScript file in your HTML document.
2. Ensure that you have sound files corresponding to each color in a "sounds" directory.
3. Press any key to start the game.
4. Repeat the sequence generated by the game by clicking on the colored buttons.
5. Try to reach the highest level possible without making a mistake.

## Disclaimer

This Simon game implementation is for educational and entertainment purposes only. enjoy!
```
