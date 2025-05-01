# Signature_verification

# Signature Verification using CNN

This project is a deep learning-based signature verification system using Convolutional Neural Networks (CNNs). It classifies signatures as genuine or forged using image data.

## Technologies Used

- Python
- TensorFlow & Keras
- OpenCV
- NumPy
- Matplotlib
- scikit-learn
- Google Colab

## Dataset Structure

The dataset is organized inside Google Drive:


## Steps Performed

1. Imported necessary libraries.
2. Mounted Google Drive to access the dataset.
3. Loaded training and test images.
4. Preprocessed image data and applied label encoding.
5. Built a CNN model using Keras Sequential API:
   - Conv2D → ReLU → MaxPooling
   - Flatten → Dense → Dropout
6. Compiled and trained the model with training data.
7. Evaluated model on test data and visualized results.

## Model Summary

- Input: Signature images (resized and grayscale)
- Output: Binary classification (genuine or forged)
- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Evaluation: Accuracy, Loss, Prediction Visualization

## How to Run

1. Open the `Signature.ipynb` notebook in Google Colab.
2. Mount Google Drive and ensure dataset path is correct.
3. Run all cells to train and test the CNN model.

## Results

The model achieves high accuracy in distinguishing genuine and forged signatures, with plotted training/validation curves and predictions displayed.

## Author

Developed by Naga Balaji 
