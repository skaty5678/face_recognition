# Facial recognition using Siamese Neural Network
A Face Recognition Siamese Network implemented using Keras. Siamese Network is used for one shot learning which do not require extensive training samples for image recognition.


## Steps involved in the process

### 1. Setup tensorflow and keras for the deep learning

### 2. Collecting the image samples
Using opencv to collect the anchor and positive images and using the lfw dataset to collect the negative images.

### 3. Loading and preprocessing images.
scaling and resizing the image to (100,100,3).
Creating the labelled dataset i.e. (anchor,positive)--> 1,1,1,1 and (anchor,negative) --> 0,0,0,0

### 4. Buidling train and test partition.

### 5.Model Engineering
Building embedding layer.

Building the distance layer.

Making the Siamese model.

### 6. Trainig the model
Setup loss and optimizer

Establishing checkpoints for the training_checkpoints

Build train step funtion and the training loop

Training the model.

### 7. Evaluating the model.
Importing the metrics.

Make predictions.

Calculate metrics.

Visualise results.

### 8. Saving the model.
Saving the model as an h5 file.

### 9. Real time verification
real time veirification using webcam.
