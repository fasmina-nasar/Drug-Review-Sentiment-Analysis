# DrugReviewSentimentAnalysis
The main aim of this project is to predict the review of the drug users according to drug name, condition they are suffering from and the rating of the drug.

Steps performed:
	• Descriptive Statistics
	• Data Visualization
	• Data pre-processing and Implementing Sentiment Analysis
	• Model Building (Random Forest) 
	
About Dataset:
Drug Review Dataset is taken from UCI Machine Learning Repository. This Dataset provides patient reviews on specific drugs along with related conditions.
The features are 'drugName' which is the name of the drug, 'condition' which is the condition the patient is suffering from, 'review' is the patient's review, 'rating' is the 10-star patient rating for the drug, 'date' is the date of the entry and the 'usefulcount' is the number of users who found the review useful. 
Here the sentiment of the 'review' is the target variable that needs to be predicted. Initially we need to convert the 'review' column to the sentiment and then use it as target variable. 
![image](https://user-images.githubusercontent.com/110358522/187799582-fc3220b4-a8d8-4968-b65a-0c9e16a74049.png)
