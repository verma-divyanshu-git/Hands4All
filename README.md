# Hands4All

![Project Logo](images/logo.png)

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Training the Model](#training-the-model)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Hands4All ASL Recognition Project is a machine learning-based project aimed at recognizing American Sign Language (ASL) gestures and converting them into text or spoken language. This project provides a tool for assisting the hearing-impaired community in communication.

## Project Structure

The project directory is organized as follows:

- `images/`: Contains images and logos related to the project.
- `MP_data/`: Directory for storing data used for training machine learning models.
- `app.py`: The main application script for running the ASL recognition system.
- `collectdata.py`: Script for collecting ASL gesture data.
- `data.py`: Script for preprocessing and managing ASL gesture data.
- `function.py`: Contains functions for image processing and feature extraction.
- `model.h5`: Pretrained machine learning model for ASL recognition.
- `trainmodel.py`: Script for training and saving machine learning models.

## Installation

To run the Hands4All ASL Recognition Project, follow these steps:

1. Clone this repository to your local machine:
 git clone https://github.com/yourusername/hands4all-asl.git
2. Install the required dependencies:  pip install -r requirements.txt
3. Ensure that you have ASL gesture images stored in the `images/` folder for recognition.

## Usage

1. Start the ASL recognition system:
python app.py


2. Open a web browser and navigate to `http://localhost:5000` to access the ASL recognition interface.

3. Use the webcam to capture ASL gestures or upload ASL gesture images for recognition.

## Training the Model

If you want to retrain the ASL recognition model, follow these steps:

1. Modify and execute `collectdata.py` to collect ASL gesture data and store it in the `MP_data/` directory.

2. Execute `trainmodel.py` to train a new ASL recognition model using the collected data. Save the model as `model.h5`.

3. Replace the existing `model.h5` with your newly trained model.

## Contributing

Contributions to this project are welcome. You can contribute by submitting bug reports, feature requests, or by creating pull requests.

## License

This project is licensed under the [MIT License](LICENSE).



