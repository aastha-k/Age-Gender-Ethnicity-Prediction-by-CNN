# Age, Gender, and Ethnicity Prediction Using CNN
This project focuses on developing a robust Convolutional Neural Network (CNN) model capable of accurately predicting demographic attributes such as age, gender, and ethnicity from facial images. This was undertaken as part of the DA322M Project.

### Introduction
In the rapidly evolving field of computer vision, accurately predicting demographic attributes such as age, gender, and ethnicity from images has become crucial. Leveraging the power of CNNs, this project aims to advance our understanding and utilization of these attributes in diverse real-world applications.

### Motivation
Understanding CNN architectures in depth allows for the development of models that can significantly enhance personalization, user experience, and provide valuable insights for various sectors such as marketing, security, and social sciences.

### Applications
Marketing and Advertising: Tailor campaigns to resonate with specific demographics. <br />
Security and Surveillance: Enhance identification in surveillance systems. <br />
Social Sciences: Provide valuable insights into human behavior across demographic groups. <br />

### Objectives
Develop a Robust Model: Design and implement a CNN architecture capable of accurately predicting age, gender, and ethnicity from images. <br />
Evaluation and Optimization: Evaluate and optimize the model using appropriate metrics. <br />
Integrate Image Upload Feature: Enable users to upload a picture and see the model’s predictions. <br />

### Methodology
Data Preprocessing: Images are converted to grayscale and resized to 48x48 pixels. <br />
Model Training: The CNN is trained on a large dataset with 70% of the data allocated for training and 30% for testing. <br />
Performance Metrics: The model's performance is measured using loss and accuracy for each demographic category. <br />

### Data
Dataset: We used a preprocessed version of the UTKFace dataset with over 20,000 images, spanning 5 ethnicities, 2 genders, and ages ranging from 0 to 116.

### Results
Ethnicity Prediction: Test loss: 0.678522 | Test Accuracy: 76.45% <br />
Age Prediction: Test loss: 0.628796 | Test Accuracy: 75.84% <br />
Gender Prediction: Test loss: 0.270137 | Test Accuracy: 88.95% <br />

### Summary
The project successfully developed a CNN model that accurately predicts age, gender, and ethnicity from facial images. The model's efficiency and accuracy demonstrate the potential of CNNs in automated demographic analysis, with applications ranging from demographic research to personalized user experiences.

### Contributors
Aastha Khandelwal (210123003) <br />
Shivam Garg (210101098)
