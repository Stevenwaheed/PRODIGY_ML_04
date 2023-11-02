# PRODIGY_ML_04

In the fourth task, I worked on a classification problem using the "Hand Gesture Recognition Database" from Kaggle. 
This database consisted of hand gestures performed by 10 different subjects, with each subject performing 10 different gestures.

To solve the classification problem, I built a neural network using TensorFlow. The neural network architecture included 7 hidden layers, and you utilized the "relu" activation function. 
For optimization, you employed the "Adam" optimizer, which is a popular choice for training deep neural networks.

During the training phase, I selected a batch size of 50 and trained the model for 30 epochs. 
The training accuracy achieved was 100%, meaning that the model correctly classified all the training examples. 
The loss value obtained was 1.0681e-07, indicating that the model's predictions were very close to the actual labels during training.

Moving on to the testing phase, I evaluated the performance of the trained model on a separate test dataset. 
The accuracy achieved on the test set was 0.999750018119812, indicating that the model was able to accurately classify the hand gestures for most of the test examples. 
The loss value on the test set was 0.0006263763061724603, implying that the model's predictions had a small deviation from the actual labels.

Overall, I successfully built and trained a neural network for hand gesture classification, achieving high accuracy on both the training and testing datasets.
