# Pneumonia-Detection
This is a binary classification project to identify presence of pneumonia from Chest X-Rays.

## Need:-
"The risk of pneumonia is immense for many, especially in developing nations where billions face energy poverty and rely on polluting forms of energy. The WHO estimates that over 4 million premature deaths occur annually from household air pollution-related diseases including pneumonia. Over 150 million people get infected with pneumonia on an annual basis especially children under 5 years old. In such regions, the problem can be further aggravated due to the dearth of medical resources and personnel. For example, in Africa’s 57 nations, a gap of 2.3 million doctors and nurses exists. For these populations, accurate and fast diagnosis means everything. It can guarantee timely access to treatment and save much needed time and money for those already experiencing poverty." - [1]

## Challenge:-
"Build an algorithm to automatically identify whether a patient is suffering from pneumonia or not by looking at chest X-ray images. The algorithm had to be extremely accurate because lives of people is at stake." - [1]

## Weights Link:- 
https://drive.google.com/file/d/1bwEy7utEJdSfI5PKAe1urmYFyGswGj8F/view?usp=share_link 

## Visualising the Data:-
![image](https://user-images.githubusercontent.com/106440078/199028061-6e1bde93-cedd-4f52-a171-7049e2f69e78.png)

## Callbacks-Detail:-
Before training the model is useful to define one or more callbacks, like ModelCheckpoint and EarlyStopping.

* ModelCheckpoint: when training requires a lot of time to achieve a good result, often many iterations are required. In this case, it is better to save a copy of the best performing model only when an epoch that improves the metrics ends.
* EarlyStopping: sometimes, during training we can notice that the generalization gap (i.e. the difference between training and validation error) starts to increase, instead of decreasing. This is a symptom of overfitting that can be solved in many ways (reducing model capacity, increasing training data, data augumentation, regularization, dropout, etc). Often a practical and efficient solution is to stop training when the generalization gap is getting worse.
![image](https://user-images.githubusercontent.com/106440078/199030010-80746d6c-2e5a-4957-9128-a182a42fcbdb.png)


## Model Architecture Plot:- 
![model](https://user-images.githubusercontent.com/106440078/199027749-ff49c49c-c8aa-4410-8ef7-6afb2a1e74d0.png)

## Model Performance Results
![image](https://user-images.githubusercontent.com/106440078/199027949-46b02f52-8a16-4db1-b6b1-5268bb9f9214.png)

![image](https://user-images.githubusercontent.com/106440078/199027863-acbbb6f1-b8bd-4991-b56a-728a007f9be8.png)

## Reference:-
[1] https://towardsdatascience.com/deep-learning-for-detecting-pneumonia-from-x-ray-images-fc9a3d9fdba8 
