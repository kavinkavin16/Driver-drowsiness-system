# Drowsiness Detection System

This Python project detects drowsiness in individuals using OpenCV and a pre-trained Convolutional Neural Network (CNN) model.

## Overview

This system utilizes computer vision techniques to monitor facial landmarks and eye states in real-time. When drowsiness is detected, an alarm sound is played to alert the individual.

## Usage

1. Clone the repository:

git clone https://github.com/yourusername/drowsiness-detection.git



2. Install dependencies:

pip install opencv-python keras pygame



3. Run the script:

python drowsiness_detection.py



## Files

- drowsiness_detection.py: Main Python script for drowsiness detection.
- alarm.wav: Alarm sound file.
- models/cnncat2.h5: Pre-trained CNN model for eye state classification.
- haar cascade files/: Directory containing Haar cascade classifiers for face and eye detection.

## How it Works

1. Detect faces using Haar cascade classifier.
2. Locate eyes within each detected face.
3. Preprocess and classify eye states using CNN model.
4. Update a score based on eye state predictions.
5. Trigger alarm if score exceeds threshold.

## Credits

- OpenCV: https://opencv.org/
- Keras: https://keras.io/
- Pygame: https://www.pygame.org/

## License

This project is licensed under the MIT License. See the LICENSE file for details.
