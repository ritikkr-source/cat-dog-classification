# Cat and Dog Image Classification using CNN

## Project Overview
This project uses a Convolutional Neural Network (CNN) built with PyTorch to classify images as either cats or dogs. The model learns visual features from images and predicts the class of a new image.

## Technologies Used
- Python
- PyTorch
- NumPy
- Jupyter Notebook

## Model Architecture
The CNN consists of:
- Three convolutional layers
- ReLU activation functions
- Max pooling layers
- Fully connected layers
- Dropout for regularization
- BCEWithLogitsLoss for binary classification
- Adam optimizer

## Dataset
The model uses the Cats and Dogs image dataset, organized into separate Cat and Dog folders.

The dataset is split into:
- 80% training data
- 20% validation data

## Training Results
- Epochs: 10
- Final training accuracy: 96.86%
- Final validation accuracy: 84.72%

These results are from the recorded training run in the notebook.

## How to Run
1. Clone or download this repository.
2. Install the required Python libraries.
3. Download and extract the Cats and Dogs dataset.
4. Update the dataset path in the notebook if needed.
5. Run the notebook cells in order.
6. Use the prediction function to classify a new image.

## Prediction
The model accepts an image, resizes it to 128 × 128 pixels, applies normalization, and predicts whether the image contains a cat or a dog.

## Future Improvements
- Use data augmentation to improve generalization.
- Experiment with pretrained CNN architectures.
- Build a web interface for image uploads and predictions.


