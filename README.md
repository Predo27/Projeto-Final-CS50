# Little Rpg
#### Description:

Little RPG is a text-based role-playing game developed in Python as my final project for Harvard’s CS50 course. The goal of the game is to provide an accessible and engaging experience that can be played directly in the terminal, focusing on strategic decision-making and simple, enjoyable gameplay mechanics. This project reflects my interest in game design as well as my understanding of programming fundamentals covered throughout the course.

The game centers around a turn-based combat system in which players choose a character class, manage health and resources, and face enemies of increasing difficulty. Although the gameplay is intentionally straightforward, it includes several layers of strategy, such as class-based abilities, cooldowns, damage variation, and decision-driven outcomes. The project was designed with clarity and readability in mind, allowing anyone to explore the codebase and understand how each component fits together.

Little RPG aims to demonstrate the core concepts learned in CS50, including functions, classes, conditionals, loops, user input handling, file organization, and clean coding practices. While simple, it is intended to be a complete, polished, and fully playable game that highlights not only what I learned but also how much I enjoyed applying those concepts creatively.

## Features

Multiple Player Classes: Players choose from distinct roles, such as Warrior, Mage, or Archer, each with unique base stats and special abilities that influence the optimal strategy.

Turn-Based Combat: Battles unfold through alternating turns, requiring players to select actions such as attacking, using abilities, or attempting to heal.

Cooldown Mechanic: Certain special attacks have cooldown periods, adding strategic depth by requiring players to plan several turns ahead. The game also displays how many turns remain before abilities can be used again.

Enemy Variety: Different enemies appear throughout the game, each with unique health values, damage ranges, and behaviors.

Boss Fight: At the end of the game, players face a stronger and more challenging boss whose difficulty encourages thoughtful resource management.

Randomized Damage: Attacks involve randomized damage within specific ranges to maintain unpredictability and replayability.

Slow-Print Text: To enhance the storytelling experience, the game uses a “slow_print” function that prints text one character at a time, simulating a narrative pace more typical of classic RPGs.


## Project Structure

The project is composed of a single Python file containing the core logic. Although contained in one file for simplicity, the code is organized into clear sections and uses object-oriented programming where appropriate.

Player Class: Defines the player’s name, role, health, damage potential, cooldowns, and special abilities. It also stores methods for performing actions such as attacking or healing.

Enemy Class: Handles enemy attributes and attack behavior during combat.

Utility Functions: Includes functions such as slow_print, ask_choice, and ask_yes_no to manage text output, user interaction, and input validation.

Main Game Loop: The core of the game where combat takes place. It handles turn progression, checks for victory and defeat, manages cooldown countdowns, and displays all relevant information to the player.

Ending Logic: After the final boss, the game determines whether the player won or lost and displays the corresponding outcome.

This structure keeps the program organized and ensures that each part of the game is clearly defined and easy to update if needed.

## How to Play

Run the program using Python. Enter your player name when prompted. Choose a character class, each offering advantages and limitations that influence combat. Engage in turn-based battles by selecting actions each turn. Manage ability cooldowns and health carefully to survive until the final boss. Defeat all enemies to complete the game. The game is entirely text-based and does not require any external libraries beyond Python’s standard modules.

## Technologies Used

Python: Core programming language used to build all logic, classes, and interactions.
Time Module: Used to create the slow-print effect that improves narrative pacing.
Random Module: Provides randomized damage values for both player and enemy attacks, making each playthrough slightly different.

## Design Decisions

While planning Little RPG, I focused on clarity, simplicity, and educational value. Some key considerations included:

Text-Based Format: Rather than using graphics libraries, I chose a terminal-based approach to prioritize code logic over visual complexity.

Object-Oriented Structure: Player and enemy classes help maintain clean, modular code that is easier to expand in the future.

Strategic Cooldowns: The cooldown mechanic prevents repetitive ability spam and forces more thoughtful decision-making.

Replayability: Randomized damage and multiple character classes encourage players to retry the game with different approaches.

## Known Limitations

Little RPG is intentionally minimalistic and does not yet include saved progress, inventory systems, or multiple story paths. Combat focus is primarily numeric rather than narrative-driven. Expanding enemy types, adding more abilities, or introducing branching outcomes could further enhance the experience.

## Future Improvements

Potential updates include: A more advanced enemy AI; Additional character classes; A full storyline with dialogue choices; An inventory or item-based system; Separation of the project into multiple files for easier maintenance.

## Conclusion

Little RPG is a simple but complete demonstration of core programming concepts learned during CS50. It reflects my growing interest in game development and serves as an example of how fundamental tools like classes, loops, user input, and randomness can come together to form an entertaining and functional project
