# Titanic Machine Learning from Disaster
The first challenge from Kaggle


## Challenge

The sinking of the Titanic is one of the most infamous shipwrecks in history.

On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this challenge, we ask you to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc). [kaggle](https://www.kaggle.com/c/titanic)

## Brief Wiki Descripition on Machine Learning

Machine learning (ML) is the study of computer algorithms that can improve automatically through experience and by the use of data. It is seen as a part of artificial intelligence. Machine learning algorithms build a model based on sample data, known as "training data", in order to make predictions or decisions without being explicitly programmed to do so. Machine learning algorithms are used in a wide variety of applications, such as in medicine, email filtering, speech recognition, and computer vision, where it is difficult or unfeasible to develop conventional algorithms to perform the needed tasks.


## How to run the code

1. Either fork or clone the repository into your computer
2. Download the dataset from Kaggle
3. Install the required libraries
4. Open the notebook 'main.ipynb'
5. Run the code

## Strategy

The first thing that came into my mind was to find the right features. Eliminate the features that didn't represent anything but noise and get the most correlated features to the target, that was if the person survived or not.

There was a single feature that was engineered and it was the Tittle Holder. This feature is boolean and tells if the person is a commoner or a title holder:

![image](https://user-images.githubusercontent.com/83870535/129712681-77619a34-519f-4912-a7df-754f815beaf6.png)

## Model

The final model was a Decision Tree Classifier with the below accuracys:

![image](https://user-images.githubusercontent.com/83870535/129712562-85b0b4af-342a-461d-a078-8df4a43f54bf.png)




