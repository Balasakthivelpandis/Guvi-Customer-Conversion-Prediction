Customer Conversion Prediction

Problem Statement
You are working for a new-age insurance company and employ mutiple outreach plans to sell term insurance to your customers. Telephonic marketing campaigns still remain one of the most effective way to reach out to people however they incur a lot of cost. Hence, it is important to identify the customers that are most likely to convert beforehand so that they can be specifically targeted via call. We are given the historical marketing data of the insurance company and are required to build a ML model that will predict if a client will subscribe to the insurance. 

Features: 
age (numeric)
job : type of job
marital : marital status
educational_qual : education status
call_type : contact communication type
day: last contact day of the month (numeric)
mon: last contact month of year
dur: last contact duration, in seconds (numeric)
num_calls: number of contacts performed during this campaign and for this client 
prev_outcome: outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")
Output variable (desired target):
y - has the client subscribed to the insurance?


Project Description :
In this project. We're going to predict if the customer will subscribe to our term insurance or not in telephonic marketing campaign using Machine Learning Models. So company's marketing campaign can become Cost and Time effective. We can first praioritly target potential clients with more effective way.

Project Insights :
For the good model fit and accuret prediction we've explore the data and done Univariate Analysis, Bivariate Analysis, Correlation Check. Data type check and take dummies.

Bivariate Analysis :
We've check and learn that which type of occupations have more chances to subscribe our term insurance policy.

Job vs Target Var

Correlation :
We've check correlation between differant variables. We can see here Duration of Call is Highly correlated to our target variable.

Corelation

We've split our dataset into 80:20 ratio for train and test purpose to fit into our various Machine Learning Models.

Then we've use 'Logistic Regression Model', 'Decision Tree Model' and 'K Neighbors Classifier Model' and check it's Accuracy Score and check our evaluation metrix AUROC Score.

