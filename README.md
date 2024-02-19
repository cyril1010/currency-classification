# Currency Classification Deep Learning Model Using Convolutional Neural Networks

This project implements a deep learning model using Convolutional Neural Networks (CNNs) to classify images of different currency notes.

## Overview

This Colab notebook aims to achieve the following objectives:

- Build and train a CNN model for currency classification.
- Generate predictions on new images and visualize the results.

## Usage

1. **Dataset Preparation**:
   - Ensure that you have access to a dataset containing images of currency notes.
   - Mount Google Drive to access the dataset.

2. **Training the Model**:
   - Define the base directory and directories for training, testing, and validation datasets.
   - Specify image dimensions, batch size, epochs, and number of classes.
   - Configure an ImageDataGenerator for data augmentation and preprocessing.
   - Train the CNN model using the prepared datasets.

3. **Model Evaluation**:
   - Evaluate the trained model's performance on the test dataset.
   - Compute and display the test accuracy and loss.

4. **Generating Predictions**:
   - Generate predictions on new images using the trained model.
   - Visualize the predicted classes along with the corresponding images.

## Dependencies

Ensure that you have the following libraries installed:

- TensorFlow
- Matplotlib

Install TensorFlow using the following command:
```bash
!pip install tensorflow
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Authors

- Cyril K U (https://github.com/cyril1010)
