# image-classification-with-CNN-keras

The hands on project on Image Classification with CNNs using Keras is divided into following tasks:

### Task 1: Introduction
- Introduction to the problem.
- Introduction to the Rhyme interface.
- Importing the required libraries and helper functions.  

### Task 2: Pre-process Data
- Importing the CIFAR-10 dataset.
- Creating a subset of the dataset which has just 3 classes instead of 10. This is done for both the training and test set.
- Randomly shuffling the newly created subset.  

### Task 3: Visualize Examples
- Plotting randomly selected examples of a given set.
- We look at some examples from training and test set along with their labels.  

### Task 4: Create Model
- Creating a Keras Sequential model.
- Creating a function to add a convolutional block to the model.
- A look at the model summary.  

### Task 5: Train the Model
- Fit the model on the subset.
- Setting the EarlyStopping callback.
- Setting the ModelCheckpoint callback.  

### Task 6: Final Predictions
- Plotting the training and validation accuracy from the training.
- Loading the best model.
- Getting predictions on the test set and displaying the results
