# Supervised-Regression
Using Deep Learning techniques, predict the coordinates (x,y) of a pixel which has a value of 255 for 1 pixel in a given 50x50 pixel grayscale image and all other pixels are 0. The pixel with a value of 255 is randomly assigned. You may generate a dataset as required for solving the problem.


<h2>Data Preparation:</h2>
Generated a dataset consisting of 50x50 grayscale images with a single pixel having a value of 255, while all other pixels are 0.
Split the dataset into training and testing sets.

<h2>Model Architecture:</h2>
Designed a neural network model architecture using TensorFlow/Keras.
The model consists of one Flatten layer followed by two Dense layers.
The output layer has two units for predicting the x and y coordinates.

<h2>Model Training:</h2>

Compiled the model using the Adam optimizer and mean squared error loss function.
Trained the model using the training data for 10 epochs, with a batch size of 32.
Monitored the training progress using training and validation loss.

<h2>Model Evaluation:</h2>

Evaluated the trained model using the test data.
Calculated the test loss, which represents the model's performance on unseen data.

<h2>Analysis and Interpretation:</h2>
Interpreted the training logs and test loss value to assess the model's performance. plotted the sccatter plot and
Considered additional evaluation metrics such as R2 score  to gain further insights into the model's accuracy.



By following this step-by-step process, I've created, trained, and evaluated a neural network model for predicting the coordinates of a single pixel in a grayscale image. 
