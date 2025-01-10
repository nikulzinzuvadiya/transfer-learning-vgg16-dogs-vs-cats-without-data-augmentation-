# transfer-learning-vgg16-dogs-vs-cats-without-data-augmentation

his repository demonstrates transfer learning using the pre-trained VGG16 model for binary image classification on the "Dogs vs. Cats" dataset. It includes a streamlined implementation for feature extraction without data augmentation, making it ideal for beginners and practitioners aiming to understand transfer learning concepts.

The project features:

1.Dataset Management:
Automatic downloading and extraction of the "Dogs vs. Cats" dataset from Kaggle.
Directory-based dataset loading for training and validation.

2.Model Architecture:
Leveraging the pre-trained VGG16 model with imagenet weights.
Adding fully connected layers for binary classification.

3.Transfer Learning:
Freezing the VGG16 convolutional base to focus on feature extraction.
Fine-tuning on the "Dogs vs. Cats" dataset.

4.Visualization:
Accuracy and loss graphs to track training progress.
