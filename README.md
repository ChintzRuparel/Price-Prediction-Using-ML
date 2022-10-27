## Price Predictions Using ML 

<h2>Problem Definition</h2>
<p>Stock Market Prediction using Linear Regression and KNN using the Tata Global Company Stock Price Dataset. </p>

<h2>Introduction</h2>
<p>Predicting how the stock market will perform is one of the most difficult things to do.There are so many factors involved in the prediction. All these aspects combine to make share prices volatile and very difficult to predict with a high degree of accuracy.Using features like the latest announcements about an organization, their quarterly revenue results, etc., machine learning techniques have the potential to unearth patterns and insights we didn’t see before, and these can be used to make unerringly accurate predictions. We have implemented a machine learning algorithms to predict the future stock price of Tata Global company using Linear Regression and KNN</p>

<h2>Linear Regression</h2>
 Linear regression algorithm shows a linear relationship between a dependent (y) and one or more independent (x) variables, hence called as linear regression.  Libraries used for Linear Regression are:1. from sklearn.model_selection import train_test_split:Sklearn train_test_split function splits a dataset into training data and test data.2. from sklearn.linear_model import LinearRegression:Sklearn LinearRegression function is a tool to build linear regression models3. from sklearn import metrics:Sklearn metrics let you assess the quality of your predictions


<h2>Implementation and Discussion</h2>
Both Linear Regression and KNN can be used to predict the future trends as:
<ul>
<li>They both can be used as technical indicators. </li>
<li>For every rise in the algorithmic value, there is a fall in the stock price</li>
<li>For every dip in the algorithmic value, there is a rise in the stock price</li>
</ul>

KNN is better than Linear Regression, since:
<ul>
<li>Lesser the RMSE Value, better is the prediction and the value is lesser in the KNN Model</li>
<li>The difference between actual and predicted value should be less and it is less in KNN than in Linear Regression</li>
</ul>


Dataset - [NSE-TATAGLOBAL11.csv](https://github.com/ChintzRuparel/Price-Prediction-Using-ML/files/9728063/NSE-TATAGLOBAL11.csv)
    
