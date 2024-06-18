**Image classification using CNNs in Keras**

**Learning Outcomes:**

 Pre-processing of image data.
 Visualization of images.
 Building CNN.
 Evaluate the Model.

⭐ **Steps and tasks:**

1. Import the libraries, load dataset, print shape of data, visualize the images in dataset.
   
2. Data Pre-processing: 
a. Normalization.
b. Gaussian Blurring.
c. Visualize data after pre-processing.

3. Make data compatible: 
a. Convert labels to one-hot-vectors.
b. Print the label for y_train[0].
c. Split the dataset into training, testing, and validation set.
(Hint: First split images and labels into training and testing set with test_size = 0.3. Then further split test data
into test and validation set with test_size = 0.5)
d. Check the shape of data, Reshape data into shapes compatible with Keras models if it’s not already. If it’s
already in the compatible shape, then comment in the notebook that it’s already in compatible shape.

4. Building CNN: 
a. Define layers.
b. Set optimizer and loss function. (Use Adam optimizer and categorical crossentropy.)

5. Fit and evaluate model and print confusion matrix.
   
6. Visualize predictions for x_test[2], x_test[3], x_test[33], x_test[36], x_test[59].
