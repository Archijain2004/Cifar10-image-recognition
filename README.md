# CIFAR-10 Image Recognition using CNN

A Convolutional Neural Network built with TensorFlow/Keras to classify images
into 10 categories using the CIFAR-10 benchmark dataset.

## Results
- **Test Accuracy:** 82.36%
- **Test Loss:** 0.529

## Architecture
3-block CNN (Conv2D + BatchNormalization + MaxPooling + Dropout), 668,842
trainable parameters, trained with real-time data augmentation (rotation,
shifting, horizontal flip).

## Files
- `Archi_Jain__Image_Recognition_using_CNN_on_CIFAR10_Dataset.ipynb` — full training and evaluation code
- `Report__Image_Recognition_using_CNN_on_CIFAR10_Dataset.pdf` — detailed project report
- `Figure1_sample_images.png` — sample images from the dataset
- `Figure2_training_validation_history.png` — accuracy/loss curves over training
- `Figure3_confusion_matrix.png` — per-class confusion matrix on the test set
- `Figure4_prediction_example.png` — example prediction on a test image

## Tech Stack
Python, TensorFlow/Keras, NumPy, Matplotlib, Seaborn, scikit-learn
