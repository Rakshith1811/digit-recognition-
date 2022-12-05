# digit-recognition-
Minor Project

• Project Name:
Artificial Intelligence May Minor Project
• Project Description:
Problem statement: Create a Deep learning model to predict the different hand written digits
ranging from 0 to 9
Context: MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello
world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten
images has served as the basis for benchmarking classification algorithms. As new machine
learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.
Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel
has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with
higher numbers meaning darker. This pixel-value is an integer between 0 and 255. The training and
test data sets have 785 columns. The first column consists of the class labels (see above), and
represents the article of clothing. The rest of the columns contain the pixel-values of the
associated image.
Dataset can be downloaded as follows
from tensorflow.keras.datasets import mnist
(x_train, x_test),(y_train,y_test) = mnist.load_data()
Details of datasets:
Each target variable for training and testexample is assigned to one of the following labels:
• 0
• 1
• 2
• 3
• 4
• 5
• 6
• 7
• 8
• 9
These labels denote the hand written digits which can be plotted as well.

Steps to consider:
1. Normalize images by dividing pixels by 255 (if required)
2. Convert labels to categories (if required)
3. Build a CNN Architecture.
4. Execute the model for appropriate number of epochs
5. Depict loss vs. val_loss on line chart
6. Depict accuracy vs. val_accuracy on line chart.
7. Generate predictions on test_data
8. Compute Confusion matrix and classification report
