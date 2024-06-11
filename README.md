# Dice App

This is a simple Flutter app that simulates rolling dice. Each press of the dice changes its face to a random number between 1 and 6.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)


## Features

- Simulates rolling dice.
- Randomly changes the dice face on each press.

## Installation

1. **Clone the repository using Android Studio:**
   - Open Android Studio.
   - Go to **File > New > Project from Version Control**.
   - In the URL field, enter the repository URL: `https://github.com/OswaldSena/Flutter_Diceapp.git`.
   - Click **Clone**.

2. **Install Flutter dependencies:**
   - Open the terminal in Android Studio.
   - Run the command:
     ```sh
     flutter pub get
     ```

3. **Run the app:**
   - Ensure an emulator or a physical device is connected.
   - Click on the **Run** button in Android Studio or use the command:
     ```sh
     flutter run
     ```

## Usage

1. Launch the app on an emulator or physical device.
2. Tap on either of the dice to roll and change the dice faces to random numbers between 1 and 6.

## Project Structure

```plaintext
lib/
└── main.dart     # Entry point of the application
assets/
└── images/
    ├── dice1.png  # Dice face 1
    ├── dice2.png  # Dice face 2
    ├── dice3.png  # Dice face 3
    ├── dice4.png  # Dice face 4
    ├── dice5.png  # Dice face 5
    └── dice6.png  # Dice face 6
pubspec.yaml      # Project configuration and dependencies
```

## Dependencies

- **flutter:** The core Flutter framework.

Ensure the following dependencies are listed in the `pubspec.yaml` file:

```yaml
dependencies:
  flutter:
    sdk: flutter
```


---

Feel free to contribute to this project by submitting issues or pull requests. Happy coding!
