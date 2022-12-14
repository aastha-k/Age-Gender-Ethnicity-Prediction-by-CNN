# Age-Gender-Ethnicity-Prediction-by-CNN

Using CNN to predict the age, gender and ethnicity of a person by using an image of their face. Model was trained on UTKFace dataset. Frameworks used are Tensorflow and OpenCV. 

First, I loaded the dataset and plotted graphs according to the 3 parameters I will be predicting. I divided age into segments based on the number of people in every age group. Then, for building a neural network, I categorized the target values for each parameter in accordance to how they were saved in the dataset filenames initially. I split the dataset into train and test and built a function to build a model. Using this function I created separate models to predict age, gender and ethnicity and then trained and tested them.

I received the following loss and accuracy statistics for each model:
- Ethnicity:
  - Test loss: 0.768933892250061
  - Test Accuracy: 0.7335489392280579
- Age:
  - Test loss: 1.028923511505127
  - Test Accuracy: 0.6709786057472229
- Gender:
  - Test loss: 0.2686367332935333
  - Test Accuracy: 0.8935601711273193
