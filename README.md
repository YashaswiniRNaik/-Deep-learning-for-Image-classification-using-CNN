# -Deep-learning-for-Image-classification-using-CNN

o Situation: Glasses detection which plays an important role in face recognition and soft biometrics for person identification.

o Task: CNN model should be able to classify the people with and without glasses.

o Action: CNN model built used to draw inference on Image augmentation.

o Result: Achieved classification by image augmentation techniques like rotation, zoom, and flipping help increase the diversity of training data, improving the model's ability to generalize and handle variations like lighting and orientation.

Inference on Image Augmentation:
Image augmentation techniques like rotation, zoom, and flipping help increase the diversity of training data, improving the model's ability to generalize and handle variations like lighting and orientation.

Explanation of Parameters in CNN:

Conv2D Filters: Extract features such as edges and textures.

Increasing filters captures more complex features.

Smaller kernel size (3x3) is common for detailed feature extraction.

MaxPooling2D: Reduces spatial dimensions and prevents overfitting.

Pool size (2x2) downsamples images by half.

Dense Layers: Fully connected layers for classification.

Nodes control the model’s capacity; too many may lead to overfitting.

Dropout: Randomly sets some layer outputs to zero during training.Helps prevent overfitting

Inference on Epochs and Batch Sizes:

Epochs: Determines how many times the model sees the entire training dataset. Too few epochs may underfit; too many may overfit.

Batch Size: Controls how many samples are processed at once. Smaller batches use less memory but may be noisier during training.

Conclusion:
The model classifies images into two classes (with and without glasses) with visualized training progress and saved model for future inference.


Skills: Python (Programming Language) · Convolutional Neural Networks (CNN) · Machine Learning · Keras · TensorFlow
