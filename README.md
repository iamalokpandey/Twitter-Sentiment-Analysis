# Twitter-Sentiment-Analysis-Project

## KEYWORDS : 
1. Supervised Learning
2. Classification Problem
3. 1D - CNN

## WORKFLOW : 
1. Dataset : Load, Visualize, Preprocess, Split, TF-IDF
2. Model : Create, Compile, Train, Evaluate

## Twitter Sentiment Analysis Dataset
  1. Total Samples : 1.6M
  2. Original Data Points : target,ids,date,flag,user,text
  3. Classes : Positive , Negative
  4. Distribution of Dat (Balanced):
  
![image](https://user-images.githubusercontent.com/52949047/181499966-447b0d45-b413-486c-9ccc-0ea9ef000da6.png)


  5. Data Preprocessing : 
    a. All Data to lowercase
    b. Url replaced with 'URL'
    c. Username replaced with 'USER'
    d. Emoji replaced with 'EMOJI' + tag
    e. words like 'yessssss' replaced with 'yes'
    f. lemmatize words
  
  ![image](https://user-images.githubusercontent.com/52949047/181706535-c42ec5e4-e6ca-498e-9ee9-ca064d002160.png)

  6. WordCloud for Negative Tweets : 
  
  ![image](https://user-images.githubusercontent.com/52949047/181500132-0122f2f6-f8c3-449a-9475-fb902d304ae6.png)

  7. WordCloud for Positive Tweets : 
  
  ![image](https://user-images.githubusercontent.com/52949047/181500225-dd98c68c-fe96-4500-abae-a8245add44c2.png)
  
  
## Models
1. Logistic Regression
2. Multinomial Naive Bayes

## Libraries
1. Re
2. Pickle : dump()
3. Numpy 
4. Pandas 
5. SeaBorn 
6. WordCloud : generate()
7. MatPlotLib
8. Nltk
9. SkLearn


## Classification Accuracy : 
1. Logistic Regression : 79%
2. Multinomial Naive Bayes : 78%

## Confusion Matrix :
1. Logistic Regression

![image](https://user-images.githubusercontent.com/52949047/181590541-f7f569a7-618b-4214-863d-dbdef7db9c7d.png)


2. Multinomial Naive Bayes


![image](https://user-images.githubusercontent.com/52949047/181590236-9b7a8587-552a-4be1-86da-d13ef5fbacd2.png)

## Classification Report : 
1. Logistic Regression

![image](https://user-images.githubusercontent.com/52949047/181590448-c781bd07-e68f-4524-a39b-019c836e7d1a.png)

2. Multinomial Naive Bayes

![image](https://user-images.githubusercontent.com/52949047/181590169-e9bd5949-43a3-4a25-aa63-33b34ee0d15b.png)
