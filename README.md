# Project3

We will use classification algorithms to predict, using the Online shopper behavior dataset, whether Revenue will be 
generated from the following features.  Administrative is the administrative web page, which is used to keep the website 
efficient and secure.  Administrative_Duration is the average time that users spend on the administrative page.  Informational 
is the information web page, which has all the general content about the website on it.  Informational_Duration is the average 
time that users spend on the information page.  ProductRelated is the product related web pages, which displays all of the products 
to consumers. ProductRelated Duration is the average time consumers spend on the product related pages.  BounceRates are the average 
times that users have left the website homepage without accessing any other pages.  ExitRates are the average times that users exited 
each page.  PageValues are the average times that a pageleads to revenue.  SpecialDay is specific days that may have more tranactions.  
Month is each month of the year.  OperatingSystems are the operating system used by the user.  Browser is the Browser used by the user.  
Region is the location of the user.  TrafficType is the average amount of people using the website at once.  VisitorType is whether the 
user is a new or reoccurrring visitor.  Weekend is whether revenue occured on the weekend.  Revenue is whether revenue was generated.  
The features that are important to predicting revenue are the ones that have a positive importance score.  A score of 0 means a feature 
has no effect on revenue and a negative score means that the feature has an inverse effect on revenue.  

The metrics that we will use to measure the model are precision, recall, accuracy, recall.  Precision is the percentage of 
true positive classifications from all positive classifications. Recall is the percentage of true positive classifications 
from all true classifications. Accuracy is the pecentage of true classifications from all classifications. f1 score is the 
harmonic mean of precision and recall.  Validate with the train and test split. 
The model Precision is higher than Recall, indicating that the model classified fewer false positives at the expense of fewer true 
positives and more true negatives at the expense of more false negatives.  The Accuracy indicates that the model classified true values 
well.  The f1 Score, weighted average between percision and recall, indicates that percision and recall are harmonic.  ROC curve measures 
the true positive rate per false positive rate.  The model ROC curve indicates that the model has a larger true positive rate than false 
positive rate.  

Classifying revenue when there is no revenue will lead to models that are built upon false revenue making assumtions and 
classifying no revenue when there is revenue will lead to models that are missing revenue making assumtions.  All of the models 
have good precision and recall, and therefore, are efficient in classifying whether revenue occured.  The models have good accuracy 
and f1 scores.  The models ROC curves all indicate that the true positive rate is larger than the false positive rate.  The feature 
that is the most likely positive predictor for revenue is PageValue, the average amount of times a page leads to revenue. 
