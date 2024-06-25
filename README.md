# Game Simulation Framework

Welcome to the Game Simulation Framework! This repository contains tools and simulations for exploring the dynamics of simple normal form games and the evolution of strategies in competitive environments. 

## Contents

1. **week1.ipynb**: Framework for simulating simple normal form games.
2. **doves_and_hawks.ipynb**: Simulation inspired by Primer's video on the evolution of aggression.

## Simulating Simple Normal Form Games

In `week1.ipynb`, we have built a framework for simulating simple normal form games based on player attributes such as size and speed. Players can adopt mixed strategies, which are probability distributions over possible actions, such as `[dodge, attack]`. The payoffs in these games are determined by the attributes of both players.

### Example Game

We have created an example game where:
- Players can choose between actions: `dodge` and `attack`.
- The payoffs are influenced by the players' size and speed attributes.
- Players can adopt mixed strategies, i.e., a probability distribution over their possible actions.

## Simulating Evolution of Aggression

In `doves_and_hawks.ipynb`, we recreate the simulation from Primer's video on the evolution of aggression. This simulation explores the interaction between two classes of players - hawks and doves - in a random environment where they compete for randomly distributed food particles.

### Key Features
- **Player Classes**: Hawks and doves, each with distinct behaviors.
- **Environment**: Players roam a random environment.
- **Competition**: Players fight over food particles, and their populations evolve over time.
- **Equilibrium Analysis**: Observe the equilibrium populations of hawks and doves and compare them with theoretical expectations.

### Future Expansions

This framework can be expanded to simulate more complex players with additional attributes such as:
- Speed
- Strength
- Resistance

By incorporating these attributes, we can simulate a wider range of behaviors and interactions.

## Contributing

We welcome contributions to enhance the framework and add new features. Please feel free to submit issues and pull requests.

## License

This project is licensed under the MIT License.


Feel free to customize further according to your needs!
