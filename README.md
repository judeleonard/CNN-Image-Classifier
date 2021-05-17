# CNN-Image-Classifier
An image detection classifier trained with keras dataset to classify images of hand labels as scissors, rock and paper. The model was used to make prediction on a new sample image. 

# Note
The model developed here was able to predict the actual shape of the class label of new sample image data, but not the label as it should. This is because of the way the data set was prepared which 
is basically for learning purposes. A good work around to have the model predict the label I feel would be to alter the inbuilt data a bit by concating train images and train labels, and test images and test labels and passing 
it through scikit-learn train_test_split to be able to capture the data labels for prediction. 
