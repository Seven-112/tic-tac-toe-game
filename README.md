![](https://img.shields.io/badge/Microverse-blueviolet)

# TIC-TAC-TOE Game

> Tic-Tac-Toe

Tic-Tac-Toe is one of the most famous games in the world. We have implemented it using only Ruby.

# Built with

- Ruby
- Object Oriented Programming

## Prerequisites

- [Ruby](https://www.ruby-lang.org/en/) must be installed on your machine.
- Text Editor

## Getting Started

1. Open Terminal.
2. Navigate to your desired location to download the contents of this repository.
3. Copy and paste the following code into the Terminal:
   `git clone https://github.com/myshine112/tic-tac-toe-game.git`
4. Run `cd tic-tac-toe-game`
5. Run `ruby bin/main.rb`

## Rules for Tic-Tac-Toe

- The game is played on a grid that's 3 squares by 3 squares.
- You are `x`, your friend is `o`. Players take turns putting their marks in empty squares.
- The first player to get 3 of her marks in a row (up, down, across, or diagonally) is the winner.
- When all 9 squares are full, the game is over. If no player has 3 marks in a row, the game ends in a tie.

```
     (1)             (2)             (3)             (4)             (5)
+---+---+---+   +---+---+---+   +---+---+---+   +---+---+---+   +---+---+---+
| 1 | 2 | 3 |   | o | x | o |   | 1 | o | o |   | x | o | x |   | x | o | o |
+---+---+---+   +---+---+---+   +---+---+---+   +---+---+---+   +---+---+---+
| 4 | 5 | 6 |   | 4 | o | x |   | x | x | x |   | x | o | 6 |   | o | x | x |
+---+---+---+   +---+---+---+   +---+---+---+   +---+---+---+   +---+---+---+
| 7 | 8 | 9 |   | x | x | o |   | o | o | x |   | x | o | o |   | x | o | o |
+---+---+---+   +---+---+---+   +---+---+---+   +---+---+---+   +---+---+---+

```

- (1) Default Game Board
- (2) Diagonal win for **o**
- (3) Horizontal win for **x**
- (4) Vertical win for **x**
- (5) Draw

## How to run the RSpec test

- You need to have the RSpec installed in you computer if you don't have it follow the steps.

Boot up your terminal and punch in gem install rspec to install RSpec. Once that’s done, you can verify your version of RSpec with rspec --version, which will output the current version of each of the packaged gems. Take a minute also to hit rspec --help and look through the various options available.

- cd into the project and open a terminal.
- In the teminal just write rspec to run the tests.
