# Galaxy-Image-Classification-using-Convolutional-Neural-Networks(CNN)

## Overview

This project focuses on developing a Convolutional Neural Network (CNN) for the detection of fake images. The dataset is structured into training and validation sets, each containing real and fake images. Leveraging TensorFlow and Keras, the CNN model is built, trained, and evaluated on a test set. Additionally, the code includes visualizations to illustrate training and validation metrics, as well as the model's predicted classifications on the test set.

## Project Structure

- `Group_Project_Data 2.zip`: Compressed file containing the dataset.
- `analysis_and_visualization.ipynb`: Jupyter notebook hosting the main code.
- `unzipped/`: Directory where the dataset is extracted.
- `README.md`: Comprehensive project documentation.

## Prerequisites

Ensure the following prerequisites are met:

- Python 3.x
- TensorFlow
- Matplotlib

## Usage

1. Upload the `Group_Project_Data 2.zip` file.
2. Run the Jupyter notebook `analysis_and_visualization.ipynb` in a step-by-step fashion.
3. Install necessary dependencies using `pip install tensorflow matplotlib`.

## Code Description

- **Data Extraction:** Unzip the dataset into the `unzipped` directory.
- **Data Preprocessing:** Define directories for training and validation, organize image paths and labels.
- **Model Architecture:** Design a CNN model with convolutional layers, max-pooling layers, dropout for regularization, and fully connected layers.
- **Model Compilation:** Compile the model with stochastic gradient descent (SGD) optimizer and binary crossentropy loss function.
- **Data Generators:** Create image data generators for training and validation with rescaling.
- **Model Training:** Train the model on the training set, and store the training history.
- **Model Evaluation:** Evaluate the model on the test set, and print accuracy.
- **Visualization:** Generate plots for accuracy, loss, and visualizations of images with predicted classifications.

## Results and Visualizations

- The final model achieves a certain accuracy on the test set.
- Plots depict training and validation accuracy/loss trends over epochs.
- Visualizations include images with predicted classifications, distinguishing correct and incorrect predictions.

## Contributors

- [Your Name]
- [Contributor 1]
- [Contributor 2]

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to tailor the README to your project specifics, providing additional details or instructions as needed.
