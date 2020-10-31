# [Amazon Alexa Reviews](https://github.com/parthshah28/Amazon_Alexa_Reviews)

![](https://github.com/parthshah28/Amazon_Alexa_Reviews/blob/main/images/download%20(1).png)

## Dataset:

* Dataset is taken from [kaggle](www.kaggle.com/sid321axn/amazon-alexa-reviews)

* Dataset has **3150 rows** and **5 columns**

* Dataset consists of 3000 Amazon customer reviews, star ratings, date of review, variant and feedback of various amazon Alexa products like Alexa Echo, Echo dots.

![](https://github.com/parthshah28/Amazon_Alexa_Reviews/blob/main/images/1.png)

![](https://github.com/parthshah28/Amazon_Alexa_Reviews/blob/main/images/2.png)

## WordCloud:

 **Positive and Negative Reviews**

<table><tr title ='Positive and Negative Reviews'><td><img src='https://github.com/parthshah28/Amazon_Alexa_Reviews/blob/main/images/3.png'></td><td><img src='https://github.com/parthshah28/Amazon_Alexa_Reviews/blob/main/images/4.png'></td></tr></table>

## Data Cleaning:

* First I have dropped **'date' and 'rating'** 
* Then I have created dummy variables for **'variation'**
* Then I have defined a pipeline to clean up all the messages.
* The pipeline performs the following: **(1) remove punctuation**, **(2) remove stopwords**
* Finaly I have used **CountVectorizer.**

## Applied Algorithms & Their Accuracy:

| Algorithm | Accuracy |
| ---    | ---    |
| MultinomialNB | 96.78 |
| LogisticRegression | 95.23 | 

For more details check [Public_Relations_Department.ipynb](https://github.com/parthshah28/Alexa/blob/main/Public_Relations_Department.ipynb)

***
