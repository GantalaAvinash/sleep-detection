# Sleep Detection using Raspberry Pi

![Sleep Detection](Sleep-Detection.mp4)

## Overview

This project aims to create a sleep detection system using a Raspberry Pi and a webcam. The system can monitor a person's eyes and detect if they are falling asleep. It will raise an alert if the person's eyes remain closed for an extended period, indicating potential drowsiness or sleepiness.

The sleep detection system utilizes computer vision techniques and machine learning algorithms to analyze facial landmarks and track eye movements. The Raspberry Pi captures video from the webcam, processes it in real-time, and alerts the user if sleepiness is detected.

## Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Hardware Requirements](#hardware-requirements)
- [Software Requirements](#software-requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Before setting up the Sleep Detection system, ensure you have the following prerequisites:

- Basic knowledge of Raspberry Pi and Linux commands.
- Familiarity with Python programming language.
- Access to a Raspberry Pi (any model with a USB port) and a compatible webcam.

## Hardware Requirements

- Raspberry Pi (any model with a USB port)
- USB webcam with a resolution of at least 720p
- MicroSD card (at least 8GB) with Raspbian OS installed
- Power supply for Raspberry Pi
- HDMI cable and monitor (for initial setup, optional)
- Internet connection (for package installation and updates)

## Software Requirements

- Raspbian OS (Lite version recommended)
- Python 3.x
- OpenCV library for Python
- dlib library for Python
- NumPy library for Python

## Installation

1. Connect the webcam to the USB port of your Raspberry Pi.

2. Ensure your Raspberry Pi is running Raspbian OS. If not, download and install the latest version of Raspbian from the official Raspberry Pi website.

3. Update the system packages by running the following commands in the terminal:

   ```
   sudo apt-get update
   sudo apt-get upgrade
   ```

4. Install the required libraries using the following commands:

   ```
   sudo apt-get install python3-opencv
   sudo apt-get install python3-dlib
   sudo apt-get install python3-numpy
   ```

5. Clone or download this GitHub repository to your Raspberry Pi:

   ```
   git clone https://github.com/your-username/sleep-detection.git
   ```

6. Change to the project directory:

   ```
   cd sleep-detection
   ```

## Usage

1. Make sure the webcam is properly connected to the Raspberry Pi.

2. Run the sleep detection script:

   ```
   python3 sleep_detection.py
   ```

3. The webcam feed will open, and the sleep detection process will begin.

4. Keep an eye on the terminal for any sleepiness alerts. The system will raise an alert if the eyes remain closed for an extended period.

5. To stop the sleep detection process, press `Ctrl + C` in the terminal.

## Contributing

Contributions to this project are welcome! If you find any issues or have ideas for improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify this project for your needs.
