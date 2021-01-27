# GoogleAppProject
Data Analytics play a very crucial role in the world today. It has benefits which lead to company or organizational growth. Data is generated in exabytes by an organization which can be used for manipulation and behavioral patterns can be studied. Analysis can be performed on any data to study the different patterns; hence we have decided to consider the data of the google play store. Google Play store is a store for applications for the Android devices. The data about the various applications can be provided by this store. The applications are from various domains which can downloaded and used. Every application has a title, version, ratings, reviews, category, price, etc. This data about the applications can be manipulated for growing the business in the world of applications. Here we are, developing a project which would help us know which application is more useful, which application domain would make more money, which genre of applications is more liked by the users, which application would gain fame, etc.


1. For this project, the main goal is to predict the which Application will make more
business(money) and what are the factors (variables) that influence the probability values.

2. We will build multiple linear regression models where:
• Y-variable: ApplicationName– This is the target of prediction. This is a Most popular
App, where 1 corresponds to most popular, and 0 corresponds to least popular in
the google App store. The values range from between 0 to 1.
• X-variables: Category, Rating, Reviews, Size, Installs, Price
We will perform feature selection method like backward and forward elimination
using p-value or AIC as metric, stepwise regression, subset regression with hold out
evaluation as the dataset is large. We are mainly going to focus on values like R2
and Adjusted R2 (more preferably Adjusted R2) i.e. goodness of fit (F test),
individual parameter test, residual Analysis and P values of independent X variables
in the model, and then predict the accuracy of the model.

3. We would also predict what Rating of the applications using the below x-variables.
For categorical variables like Genres and Category we would like to apply some supervised
learning techniques for classification like Logistic regression.
• Y-variable: Rating: -Showed in decimal rating of the application with maximum at 5
and minimum at 0.
• X-variables: Category, Reviews, Installs, Type, Price
- we can use hold-out evaluation for the entire dataset and find the accuracy for
which of the Application is maximum download according to the rating.We can
create boxplots and graphs of Category, Tpye, Genres, to see if performing actions
have any effect on the chances of maximum rating.

4. - Since there are a lot of variables, multicollinearity problem is sure to exist. We can check
the correlations of the x-variables and eliminate the variables which have high correlations
with other variables.

5. Hypothesis testing: Application downloading dependent on the type of the Application
H0: The Application type is Paid
H1: The Application type is not Paid (Free)
6. Some columns of the dataset contain Missing value, null values and data redundancy.
