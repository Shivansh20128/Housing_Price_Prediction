# Breast Cancer Classifier using Neural Network
This is a neural network classification model for identifying breast cancer tumor as malignant or benign.

# Dataset
The first step for any machine learning and deep learning model is getting the dataset and pre-processing it.

For this model, we will use an sklearn dataset, and download it in runtime. We will store that dataset into a dataframe and perform some operations on it (like scaling) to prepare it for training.

At the end of this step, we will split the dataset into train and test sets.

# Model
In this step, we will initialize and define our neural network model. For this case, we are going to use a single hidden layer network. We will also be using the keras library to flatten to dataset instead of doing it manually.

We will compile the model and train it on the training set.

# Visualization and Results
After training the model, we can test our model using metrics like accuracy and losses. For that, we can make plots on accuracy and loss to asses the learning process. We also make predictions on our dataset and get an accuracy of 96%, which is very good indication of performance for our model.

At the end, we also create a way to get individual predictions by getting a sample from the dataset and converting it to a form which can be fed to our model.