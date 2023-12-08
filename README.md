#                                                        Celebrity Classification using CNN
## Overview
This project focuses on building a Convolutional Neural Network (CNN) to classify images of celebrities. The CNN is trained on a dataset consisting of images of various celebrities, and the model is then evaluated on a test set. Additionally, the project includes a function to make predictions on new images.
## Dataset
## Directory Structure
*	The dataset is organized into subfolders, each representing a different celebrity.
*	Located in the "Dataset_Celebrities" directory.
## Data Loading and Preprocessing
*	Images are loaded using OpenCV and PIL libraries.
*	Images are resized to (128, 128) pixels.
## Code Structure
* celebrity_accuracy_plot.png: Plot showing accuracy and validation accuracy.
*	celebrity_loss_plot.png: Plot showing loss and validation loss.
## How to Run
*	Clone the repository.
*	Open and run the celebrity_classification.py
*	Trained model will be saved, and plots generated.
 * 	Use the make_prediction function for new image predictions.
## Model Architecture
*	CNN architecture includes convolutional layers, max-pooling layers, flattening layer, and dense layers.
*	Output layer uses softmax activation for multi-class classification.
## Results
* The model is tested on sample images for each celebrity to demonstrate its prediction capabilities
