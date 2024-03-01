# deep-learning-challenge

Overview
The purpose of this analysis is to create a deep learning model for binary classification using dataset. There were various different features that were used to predict the target variable. This modeling required preprocessing of the data, creating the model and training. Finally evaluating the performance to see if tuning needs to be done for better results.

Data Preprocessing
    - The target variable for my models were "IS_SUCCESSFUL".
    - The feature varibales were all the columns except "IS_SUCCESSFUL". 
    - There were two columns that were removed due to lack of usefulness (['EIN', 'NAME']).

Compiling, Training, and Evaluating the Model
    - a total of 3 models were made in an attempt to reach 75% accuracy. 
        - Model 1: 3 layers / 256, 128, 1 nueron / Activation = 'relu', 'relu', 'sigmoid' / Accuracy: 72.9%
        - Model 2: 3 layers / 128, 64, 1 nueron / Activation = 'relu', 'relu', 'sigmoid' / Accuracy: 58.2%
        - Model 3: 3 layers / 9, 18, 1 nueron / Activation = 'relu', 'relu', 'sigmoid' / Accuracy: 73.1%
    - Unfortunately after many attempts i was unable to achieve the goal of 75% accuracy.
    - The steps i tried to make to increase model perfomance was adjusting epoch amount, and neurons. Including dropout layers to precent overfitting. 

Summary
In conclusion deep learning models requires a good understanding of preprocessing the data. Understanding the features, variables, and what can be dropped is essential when training for these types of models. Recommend using different number of layers and number of nuerons per layer. Find one that works for the certain tasks. Sometimes simple networks perform better. Exploring different hyperparameters like learing rate, batch size, and epochs are nessesary to find the best combination for the model.
    
