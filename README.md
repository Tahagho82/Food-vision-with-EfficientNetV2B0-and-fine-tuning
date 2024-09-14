# Food-vision-with-EfficientNetV2B0-and-fine-tuning🍕🍔🍟🌭🥓🍳🧈

This project demonstrates transfer learning with the EfficientNetV2B0 model for image classification on a food dataset. It includes the following steps:

Data preparation: Downloading, extracting, and exploring the dataset.
Data augmentation: Creating a data augmentation layer to artificially expand the dataset.
Transfer learning:
Utilizing a pre-trained EfficientNetV2B0 model and freezing its layers.
Adding a classification head for the food dataset.
Model training: Training the model with an Adam optimizer and monitoring performance with TensorBoard.
Fine-tuning: Unfreezing a portion of the base model's layers and retraining with a reduced learning rate.
Evaluation: Comparing performance before and after fine-tuning, and visualizing predictions.
This project effectively showcases how to leverage pre-trained models and fine-tuning techniques to achieve good performance on a new image classification task, even with limited data.
