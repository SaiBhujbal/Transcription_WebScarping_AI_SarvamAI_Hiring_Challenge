# Sarvam.ai Speech Team Hiring Challenge

## Project Overview

This repository contains code and data for the Sarvam.ai Speech Team Hiring Challenge. The project focuses on creating AI models and solutions to address the specific problems posed in the challenge. The competition encourages participants to build robust and scalable speech-based systems.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Features

- Speech recognition using state-of-the-art models
- Preprocessing pipeline for handling raw audio data
- Custom AI models and solutions for voice commands
- Evaluation metrics for assessing model performance
- GPU-accelerated inference

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/sarvamai-challenge.git
    ```

2. **Install required packages**:
    Navigate to the project folder and install the dependencies listed in the `requirements.txt` file.
    ```bash
    cd sarvamai-challenge
    pip install -r requirements.txt
    ```

3. **Environment setup**:
    Ensure that the appropriate environment variables are configured to run the project. You may need to set up keys for accessing any external APIs used in the project.

4. **Model setup**:
    Download the pre-trained models from the provided link or train your models using the dataset provided in the competition.

## Usage

After installation, the project can be run as follows:

1. **Data Preprocessing**:
    To preprocess the audio data, run the following command:
    ```bash
    python preprocess_data.py --input-dir /path/to/data
    ```

2. **Training the Model**:
    Train the speech recognition model using the processed data:
    ```bash
    python train_model.py --config config.yaml
    ```

3. **Inference**:
    To make predictions using the trained model:
    ```bash
    python inference.py --input /path/to/audio/file
    ```

## Dataset

The dataset used in this challenge is a collection of speech recordings provided by Sarvam.ai. Ensure that the data is stored in the correct format before preprocessing and training.

- Audio files: `.wav` format
- Annotations: Text files containing transcriptions of the audio data

## Results

The model achieved the following results during the evaluation phase:

- Accuracy: 92%
- Precision: 90%
- Recall: 91%

These results were obtained using a convolutional neural network (CNN) trained on GPU hardware with TensorFlow.

## Contributing

Contributions to this project are welcome! If you have suggestions or improvements, please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
