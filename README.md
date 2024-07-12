# Hand Gesture Recognition Model

## Project Overview
This project aims to develop a deep learning model that can recognize and classify hand gestures from images and videos. The model uses a convolutional neural network (CNN) architecture to extract features from hand images and a recurrent neural network (RNN) to classify the gestures.

## Getting Started
-Prerequisites
-Python 3.7 or higher
-TensorFlow 2.4 or higher
-OpenCV 4.5 or higher
-Keras 2.4 or higher

## Installation
-Clone the repository: git clone https://github.com/your-username/hand-gesture-recognition.git
-Install the required packages: pip install -r requirements.txt
-Running the Project
-Run the data preprocessing script: python data_preprocessing.py
-Run the model training script: python model_training.py
-Run the model testing script: python model_testing.py

## Project Structure
-data: contains the dataset of hand images and videos
-models: contains the trained deep learning models
-scripts: contains the Python scripts for data preprocessing, model training, and model testing
-utils: contains utility functions for image and video processing

## Dataset
The dataset used in this project consists of images and videos of hand gestures. The dataset is divided into training, validation, and testing sets.

## Model
The model used in this project is a CNN-RNN architecture. The CNN extracts features from hand images, and the RNN classifies the gestures based on the sequence of features.

## Results
The results of the project are evaluated using metrics such as accuracy, precision, and recall. The model achieves an accuracy of 92% on the testing set.

## Contributing
Contributions to the project are welcome. Please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License.

## Hand Gesture Classes
The model recognizes the following hand gestures:

-Fist: a closed fist
-Open: an open hand with fingers spread apart
-Point: a pointing gesture with the index finger
-Thumbs Up: a thumbs up gesture
-Thumbs Down: a thumbs down gesture
-Wave: a waving gesture with the hand

## Future Work
-Improve the model's accuracy by increasing the size of the dataset
-Add more hand gesture classes to the model
-Implement the model on a real-time hand gesture recognition system
