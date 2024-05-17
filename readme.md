# Shredder Safety Alert System

## Overview

The Shredder Safety Alert System is a Python-based application designed to enhance the safety of shredding machines. This system uses TensorFlow Object Detection to detect when a hand crosses the safety line of a shredding machine and triggers an alert to warn the user.

## Features

- Real-time hand detection using TensorFlow Object Detection
- Alerts when a hand goes beyond the safety line
- Easy to set up and run

## Prerequisites

- Python 3.7
- Conda for environment management
- Webcam or camera for real-time hand detection

## Installation

1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/your-username/shredder-safety-alert.git
    cd shreddersystem
    ```

2. Create a Conda environment with Python 3.7:
    ```bash
    conda create --name shredder-env python=3.7
    conda activate shredder-env
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Navigate to the project directory:
    ```bash
    cd shreddersystem
    ```

2. Run the hand detection script:
    ```bash
    python hand_detection.py
    ```

## Project Structure

- `hand_detection.py`: Main script to run the hand detection and alert system.
- `requirements.txt`: List of dependencies required to run the project.
- `README.md`: Project documentation.

## Dependencies

Ensure you have the following dependencies installed, which are listed in `requirements.txt`:

- TensorFlow
- OpenCV
- Numpy
- Other dependencies required for TensorFlow Object Detection

## Contributing

If you wish to contribute to this project, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- [TensorFlow](https://www.tensorflow.org/) for providing the object detection API.
- [OpenCV](https://opencv.org/) for providing the computer vision tools.
