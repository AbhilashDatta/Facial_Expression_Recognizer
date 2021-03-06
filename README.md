# Facial_Expression_Recognizer

## Task 1: Imports
Import essential modules and helper functions from NumPy, Matplotlib, and Keras.

## Task 2: Exploring Dataset
Display some images from every expression type in the Emotion FER dataset.
Check for class imbalance problems in the training data.

## Task 3: Generate Training and Validation Batches
Generate batches of tensor image data with real-time data augmentation.
Specify paths to training and validation image directories and generates batches of augmented data.

## Task 4: Create a Convolutional Neural Network (CNN) Model
Design a convolutional neural network with 4 convolution layers and 2 fully connected layers to predict 7 types of facial expressions.
Use Adam as the optimizer, categorical crossentropy as the loss function, and accuracy as the evaluation metric.

## Task 5: Train and Evaluate Model
Train the CNN by invoking the model.fit() method.
Use ModelCheckpoint() to save the weights associated with the higher validation accuracy.
Observe live training loss and accuracy  plots in Jupyter Notebook for Keras.

## Task 6: Save and Serialize Model as JSON String
Sometimes, you are only interested in the architecture of the model, and  you don't need to save the weight values or the optimizer.
Use to_json(), which uses a JSON string, to store the model architecture.
