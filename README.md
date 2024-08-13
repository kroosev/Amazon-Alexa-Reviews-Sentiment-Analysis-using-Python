# Amazon-Alexa-Reviews-Sentiment-Analysis-using-Python
Amazon Alexa is a cloud-based voice service developed by Amazon that allows customers to interact with technology.
The dataset I’m using for the task of sentiment analysis of Amazon Alexa reviews was collected from Kaggle. It contains data about ratings between 1 and 5, the date of reviews, and customer feedback on their experience with Alexa. 
First, the necessary Python dataset and libraries that we need for this task are imported.
The dataset’s rating column contains the ratings given by the users of Amazon Alexa on a scale of 1 to 5, where 5 is the best rating a user can give. Breakdown of ratings given to Amazon Alexa by its users is printed. From the figure, we can see that most of the customers have rated Amazon Alexa including all its variants as 5. So it means that most of the customers are happy with Amazon Alexa. 
The verified_reviews column of the dataset contains all the reviews given by Amazon Alexa’s customers. So new columns are added to this data as positive, negative and neutral by calculating the sentiment scores of the reviews. 
The sentiment scores for each column are calculated to understand what most of the customers of Amazon Alexa think about it.
The final output that we get is therefore neutral. This means that most users feel neutral about Amazon Alexa services. Now the sum of the sentiment scores for each column is calculated.

So we can see that Positive and Neutral are above 1000 where Negative is below 100. So this means that most of the customers of Amazon Alexa are satisfied with its services.
