# Titanic-Survivor-Prediction
Titanic Survivor Prediction Using Decision Trees 

Titanic Survivor Prediction
Use your ML Skills to predict who will survive?
Cody and his friends decided to go on a cruise for vacation.Their cruise was named TITANIC-2 and is a complete replica of the famous titanic ship.



One of Cody's friend is paranoid on boarding the cruise as he recently watched the titanic movie and is certain if the cruise sinks he won't survive.

Cody being a good friend, decided to put his friends mind to rest by collecting data from actual titanic accident .

Now your job is to develop a model based on data collected by Cody to predict whether a given passenger will survive or not, which Cody will then use to satisfy his friend's curiosity!

Data Description
Dataset Consist of two files "Train.csv" and "Test.csv" you have to train your model on 'Train.csv' and predict the output on 'Tets.csv' ,then submit the output in the form of "sample_submission.csv ".

Data Dictionary
Variable      Definition          Key
------------------------------------------------------------------
survival         Survival           0 = No, 1 = Yes

pclass          Ticket class   1 = 1st, 2 = 2nd, 3 = 3rd

sex                  Sex   

Age                 Age in years   

sibsp        # of siblings / spouses aboard the Titanic  

parch        # of parents / children aboard the Titanic  

ticket        Ticket number   

fare            Passenger fare  

cabin         Cabin number   

embarked    Port of Embarkation    C = Cherbourg, Q = Queenstown, S = Southampton
Variable Notes
pclass : A proxy for socio-economic status (SES)

1st = Upper

2nd = Middle

3rd = Lower

age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

sibsp: The dataset defines family relations in this way…

Sibling = brother, sister, stepbrother, stepsister

Spouse = husband, wife (mistresses and fiancés were ignored)

parch: The dataset defines family relations in this way…

Parent = mother, father

Child = daughter, son, stepdaughter, stepson

Some children traveled only with a nanny, therefore parch=0 for them.
