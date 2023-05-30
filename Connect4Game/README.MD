# Connect 4 Game with Python and Pygame

This project is a multiplayer game of Connect 4 implemented in Python using the Pygame library and socket programming.

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Authors](#authors)
- [Acknowledgments](#acknowledgments)

## Description

Connect 4 is a classic game where two players take turns dropping colored pieces into a vertical grid. The goal of the game is to get four pieces in a row (horizontally, vertically, or diagonally) before your opponent does. This project implements the game using Python and Pygame, with socket programming for multiplayer functionality.

## Installation

To install and run the game, follow these steps:

1. Clone this repository to your local machine.
2. Make sure you have Python 3.x installed on your machine.
3. Install the Pygame library by running the following command in your terminal: pip install pygame
4. Run the server code by navigating to the repository folder in your terminal and running the following command: python server.py
5. Run the client code on a separate machine by navigating to the repository folder in your terminal and running the following command: python client.py

## Usage

Once the client has successfully connected to the server, the game will begin. Players will take turns dropping their colored pieces into the game board by clicking on the desired column in the game window. The first player to get four pieces in a row (horizontally, vertically, or diagonally) wins the game.



## Authors

- [Mohamed Gad](https://github.com/MuhamedGad) - Initial work

## Acknowledgments

- The game logic for Connect 4 was based on the implementation by [KeithGalli](https://github.com/KeithGalli) found at [Connect4-Python](https://github.com/KeithGalli/Connect4-Python).
- The Pygame library was used to create the game window and handle user input.
- Inspiration and guidance for implementing the multiplayer functionality came from [Real Python](https://realpython.com/python-sockets/).

## Conclusion

Thank you for playing Connect 4 with Python and Pygame!We hope you enjoy the game and find this README file helpful. If you have any questions or feedback, please don't hesitate to reach out.

