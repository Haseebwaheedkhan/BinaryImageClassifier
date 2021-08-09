# BinaryImageClassifier
Machine learning model that can classify between images of T-shirts and dress-shirts.
Attached are given the following files:
• TrainData.csv: It contains 12000 training examples. Each row contains 784 values. The dataset has been derived from Fashion-MNIST dataset. 
Each example is a flattened 28x28 pixel gray-scale image. You can reshape the examples to visualize what each image looks
like.
• TrainLabels.csv: This file contains true labels for the examples in TrainExamples.csv
• TestData.csv: This file contains test examples.

# Clink on the link to download this file: 
https://drive.google.com/drive/folders/1GsAEzi02glVEH2FdtzC8WwSzzOmeDJlt?usp=sharing

Method
• Model has been trained using your extracted features method i.e HOG. SVM and Logistic Regression models i.e classification techniques are used. 
• Using 5-fold cross-validation, hyperparameters for the models are optimized. Since the dataset is balanced, I have used classification accuracy as the performance metric.
• Uses regularization and see its impact using the learning curve to choose the best lambda parameter.
• After choosing the best hyperparameters, I've used the complete training dataset to train the final model. 
• Dump the model in the file named “myModel.pkl”. 
• Generated Predictions for the test examples and save them to a csv file named “myPredictions.csv”.

