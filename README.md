# Pneumonia Detection Using CNN

This project uses a Convolutional Neural Network (CNN) to detect pneumonia from chest X-ray images. The CNN is trained on a labeled dataset of chest X-ray images and achieves high accuracy in distinguishing between normal and pneumonia cases.

## Project Structure

1. **Data Preparation**:
   - Preprocesses the images by converting them to grayscale and resizing them.
   - Normalizes the pixel values and encodes the labels.

2. **Model Training**:
   - Defines the CNN architecture using Keras.
   - Trains the model on the preprocessed training data.
   - Evaluates the model on the test data.

3. **Result Evaluation**:
   - Loads the trained model.
   - Tests the model on new images and displays the predictions.

## Files

- `01_Pneumonia detection using CNN initialisation.ipynb`: Data preprocessing and preparation.
- `02_Pneumonia detection, training the CNN - Instantiation.ipynb`: Model definition, training, and evaluation.
- `03_Pneumonia detection using CNN checking results.ipynb`: Loading the model and testing it on new images.

## Requirements

- TensorFlow
- Keras
- NumPy
- OpenCV
- os

## Installation

Install the required packages using pip:

```bash
pip install tensorflow keras numpy opencv-python
