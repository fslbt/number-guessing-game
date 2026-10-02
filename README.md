# Number Guessing Game

A command-line number guessing game written in Go.

The player chooses a difficulty level and tries to guess a randomly generated number between 1 and 100. The game includes a live timer, attempt tracking, replay support, and an in-memory highscore list.

## Features

- Random number between 1 and 100
- Three difficulty levels:
  - Easy: 10 attempts
  - Medium: 5 attempts
  - Hard: 3 attempts
- Feedback indicating whether the target number is higher or lower
- Live elapsed-time display while playing
- In-memory highscore tracking
- Replay support

## Go Concepts

This project demonstrates several Go concepts:

- Structs
- Maps
- Slices
- Functions
- Loops and control flow
- Random number generation
- Goroutines
- Channels
- Timers
- Sorting

## How to Run

Make sure Go is installed, then run:

~~~bash
go run main.go
~~~

## How to Play

1. Start the program.
2. Select a difficulty level by entering `1`, `2`, or `3`.
3. Guess the number between 1 and 100.
4. Use the feedback after each incorrect guess to adjust your next guess.
5. If you guess correctly, your number of attempts is added to the in-memory highscore list.
6. Choose whether to play another round.

## Project Structure

~~~text
number-guessing-game/
├── go.mod
├── main.go
└── README.md
~~~

## Technologies

- Go
- Standard library

## Purpose

This project was built to practice Go programming fundamentals while implementing an interactive command-line application.
