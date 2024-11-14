# Rock Paper Scissors Game with Mediapipe and OpenCV

This project implements a Rock Paper Scissors game using computer vision techniques powered by OpenCV and Mediapipe. Players can make gestures representing rock, paper, or scissors, and the program detects the gestures and determines the game's outcome against a randomly chosen move from the AI.

## Project Description
This Rock Paper Scissors game uses real-time hand gesture detection to allow players to compete against an AI. The AI's move is randomly selected, and the program determines the winner based on the rules of the classic game. The hand gestures are detected using Mediapipe's Hand Detection module, and OpenCV is used for image processing and displaying the game.

## Features
- Real-time hand gesture recognition using Mediapipe.
- Simple and interactive graphical interface with a game timer.
- AI opponent with random move selection.
- Scoring system to keep track of player and AI wins.
- Smooth and efficient hand tracking using the Mediapipe library.

![Rock beats paper - point to computer](path/to/rock_sample.png)
![Paper beats rock - point to player](path/to/paper_sample.png)
![Tie - no points](path/to/scissors_sample.png)

## Dependencies
- `Python 3.x`
- `opencv-python`
- `mediapipe`
- `numpy`
- Any additional image files for the game background and AI moves (rock, paper, scissors images)

## How It Works

1. **Camera Initialization**: The webcam is initialized using OpenCV to capture real-time video frames.
2. **Hand Detection**: Mediapipe's Hand Detection module is used to detect and track hand landmarks.
3. **Gesture Recognition**: The position of various finger landmarks is analyzed to identify gestures for rock, paper, or scissors.
4. **AI Move Selection**: The AI selects a random move each round.
5. **Overlay and Display**: The current frame is displayed with the player's move and AI's move overlaid on the game background.
6. **Scoring**: The winner is determined based on classic Rock Paper Scissors rules, and the scores are updated.

