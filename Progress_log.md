
### PROGRESS_LOG.md

```markdown
# Progress Log

## 01_Pneumonia Detection Using CNN Initialization

1. **Installed Dependencies**: Ensured the necessary packages are installed.
2. **Imported Libraries**: Imported TensorFlow, Keras, NumPy, os, and OpenCV.
3. **Dataset Preparation**: Defined data paths and categories. Initialized labels and created a label dictionary.
4. **Loaded and Preprocessed Images**: Read images, converted to grayscale, resized to 128x128, and normalized.
5. **Shuffled the Dataset**: Shuffled the dataset to ensure randomness.
6. **Prepared Data Arrays**: Separated features and labels, normalized data, and converted labels to categorical format.
7. **Saved Preprocessed Data**: Saved the image data and labels as `.npy` files.

## 02_Pneumonia Detection - Training the CNN

1. **Loaded Preprocessed Data**: Loaded the image data and labels from `.npy` files.
2. **Split Data**: Divided the data into training and testing sets.
3. **Defined the CNN Model**: Built the CNN architecture with convolutional layers, max pooling, dropout, and dense layers.
4. **Compiled the Model**: Set the optimizer, loss function, and metrics.
5. **Trained the Model**: Trained the model on the training data and saved the training history.
6. **Evaluated the Model**: Evaluated the model on the test data and printed accuracy and loss values.
7. **Saved the Model**: Saved the trained model to a file.

## 03_Pneumonia Detection Using CNN - Checking Results

1. **Loaded the Trained CNN**: Reconstructed the model and loaded the weights.
2. **Preprocessed Test Images**: Read test images, converted to grayscale, resized, normalized, and reshaped.
3. **Tested the Model**: Predicted the class for each test image and displayed the results.
