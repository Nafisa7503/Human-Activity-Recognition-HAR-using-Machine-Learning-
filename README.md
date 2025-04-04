# Human-Activity-Recognition-HAR-using-Machine-Learning-
📊 Dataset: UCI HAR (smartphone sensor data)  🎯 Goal: Classify daily activities (walk, sit, stand, etc.)  🤖 Models: SVM, KNN, Random Forest, Neural Networks  ⚙️ Steps: Preprocessing, training, evaluation  📈 Output: Accuracy, F1-score, confusion matrix

Introduction

Our project centers around the Human Activity Recognition (HAR) database, capturing daily activities using smartphone sensors. With participants engaged in diverse activities, such as walking, standing, and more, our goal is to employ machine learning algorithms to accurately classify these activities. Motivated by the growing significance of activity recognition, especially in healthcare and smart environments, we aim to address challenges in classification accuracy. By exploring various algorithms and preprocessing techniques, we seek to determine the most effective approach. The project aims to identify the algorithm with the highest accuracy and visualize results through graphs and confusion matrices, contributing valuable insights to the field.

Dataset Description:
Source:

Link:
https://www.kaggle.com/datasets/uciml/human-activity-recognition-with-smartphones

Reference:
Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. A Public Domain Dataset for Human Activity Recognition Using Smartphones. 21st European Symposium on Artificial Neural Networks, Computational Intelligence and Machine Learning, ESANN 2013. Bruges, Belgium 24-26 April 2013.

Dataset Description:

There are 563 features in our initial Dataset while one of those 563 features was our Target label, “Activity”. The problem is classification based as we have categories by which we classify the data output values. The target label Activity has 6 classifications: Standing, Sitting, Laying, Walking, Walking_downstairs and Walking_upstairs. After combining the datasets, there are 10299 data points in our Dataset. Among the 563 features, 562 are Quantitative while only the target feature, Activity, is categorical. The correlation heatmap of all the features of the database has been shown below:


