# Rock-Paper-Scissors Game

A simple Rock-Paper-Scissors game implemented in Python, allowing a user to play against the computer.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Flowchart](#flowchart)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project is a basic implementation of the classic Rock-Paper-Scissors game. The user plays against the computer, which makes random choices.

## Features

- User can input their choice of rock, paper, or scissors.
- Computer randomly selects its choice.
- The game determines and displays the winner.
- Option to play multiple rounds.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/rock-paper-scissors.git
    ```

2. Navigate to the project directory:

    ```bash
    cd rock-paper-scissors
    ```

3. (Optional) Create and activate a virtual environment:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

4. Install any necessary dependencies (none required for this basic script).

## Usage

1. Run the game:

    ```bash
    python rock_paper_scissors.py
    ```

2. Follow the on-screen prompts to play the game.

## Flowchart

Below is the flowchart representing the game's logic:

```mermaid
flowchart TD
    A[Start] --> B[Get User Choice]
    B --> C{Valid Choice?}
    C -- No --> B
    C -- Yes --> D[Generate Computer Choice]
    D --> E[Display Choices]
    E --> F[Determine Winner]
    F --> G[Display Result]
    G --> H{Play Again?}
    H -- Yes --> B
    H -- No --> I[End]


