# Catch The Kenny Game

Catch The Kenny is a simple and fun game built with Swift and UIKit. The aim of the game is to tap on the randomly appearing Kenny images as many times as possible before the time runs out. Your score will be recorded, and you can try to beat your high score!

## Features

- Randomly appearing Kenny images
- User can tap to catch Kenny and increase the score
- Countdown timer for the game duration
- High score is saved locally using `UserDefaults`
- Simple UI and intuitive gameplay

## Screenshots

![Game Screenshot](path/to/your/screenshot.png)

## Requirements

- iOS 13.0+
- Xcode 12.0+
- Swift 5.0+

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Researcher0619/CatchTheKennyGame..git
    ```
2. Open the project in Xcode:
    ```bash
    cd CatchTheKennyGame.
    open CatchTheKennyGame.xcodeproj
    ```
3. Build and run the project on your preferred iOS simulator or device.

## How to Play

1. Launch the app.
2. Kenny will appear randomly in one of the nine spots.
3. Tap on Kenny as quickly as you can to increase your score.
4. The game lasts for 10 seconds. Your final score will be displayed along with an option to replay.
5. Try to beat your high score each time!

## Code Overview

### ViewController.swift

- `score`: Keeps track of the player's score.
- `counter`: Represents the countdown timer (starts at 10 seconds).
- `kennyArray`: An array that holds all Kenny `UIImageView` instances.
- `hideKenny()`: Function that hides all Kenny images and shows one randomly.
- `increaseScore()`: Function that increments the score when Kenny is tapped.
- `countDown()`: Function that handles the countdown timer and checks if the time is up.
- `UserDefaults`: Used to store and retrieve the high score.

### Main Flow

1. The game starts with a countdown of 10 seconds.
2. Kenny images appear and disappear randomly on the screen every 0.3 seconds.
3. Players tap on the Kenny images to score points.
4. When the time reaches zero, the player's score is compared with the high score.
5. If the score is higher than the previous high score, it is saved as the new high score.
6. The player can choose to play again or exit.

## Contributing

Feel free to contribute to this project by submitti
