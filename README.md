# CNN_Plant_Disease_Prediction


Problem Statement:
The aim of this project is to develop a deep learning model using Convolutional Neural Networks (CNNs) to accurately classify and predict plant diseases from images of plant leaves. The model will help farmers and agricultural experts identify diseases early, enabling timely interventions to prevent crop damage and yield loss.

About Dataset:
The project will use a dataset containing images of plant leaves affected by various diseases, along with corresponding labels indicating the disease type. The dataset will be divided into training, validation, and test sets for model development and evaluation.

Steps Performed : 
1. Preprocess the image dataset to enhance model performance.
2. Develop a CNN model architecture for plant disease classification.
3. Train the model using the training dataset and validate it using the validation dataset.
4. Fine-tune the model to improve performance.
5. Evaluate the model using the test dataset and measure its accuracy, precision, recall, and F1 score.
6. Deploy the trained model as a web application for real-time disease prediction.

Outcome : 
The model seems to be performing quite well on the training data, with a loss of 0.0761 and an accuracy of 97.60%. However, there seems to be some overfitting, as the validation loss is higher at 0.5091 and the validation accuracy is lower at 88.28%. This suggests that the model might be memorizing the training data instead of generalizing well to unseen data. Regularization techniques like dropout or early stopping could be used to mitigate overfitting.
