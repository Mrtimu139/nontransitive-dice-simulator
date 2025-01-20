# nontransitive-dice-simulator
Initial release of the Generalized Non-Transitive Dice Game. Includes fair random number generation, configurable dice, HMAC-based validation protocol, help table with probabilities, and modular class design for flexibility and scalability.

# Generalized Non-Transitive Dice Game

This project implements a command-line-based non-transitive dice game with the following features:
- **Fair Random Number Generation:** A cryptographically secure protocol ensures fairness, using HMAC and modular arithmetic.
- **Configurable Dice:** Players can specify any number of dice with custom sides.
- **Help Table:** Displays the probability of winning for each dice pair in the game.
- **Robust Input Handling:** Validates dice configurations and handles errors gracefully.
- **Modular Design:** Follows clean coding principles with separate classes for each responsibility.

## **Features**
- Fair random number generation using cryptographic keys (HMAC-SHA3).
- Support for any number of dice with arbitrary sides.
- Interactive gameplay with user and computer participation.
- Probability table for analyzing dice pairs.
- Error handling for invalid configurations.

## **Usage**
1. Install [Node.js](https://nodejs.org/).
2. Clone the repository and navigate to the project folder:
   ```bash
