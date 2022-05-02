# YES-BANK-STOCK-PRICE-PREDICTION




 Yes-Bank is a well-known bank in the Indian Financial Domain. Since 2018, It has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that affected the stock prices of the company. This dataset has monthly stock prices of the bank since its establishment which includes features like closing , starting , highest , & lowest stock prices of every month. The Main objective is to predict the Stock’s Closing Price of the month.
Important points:-
1.	Dataset consists of 185 observations and 5 features such as “Date”, ”Open”, ”High”, ”Low”, ”Close”.

2.	The feature “Date” which is a object data type and also the format of “Date” is in MMMM-YY, So we need to convert it in proper date format i.e. in the format YYYY-MM-DD.

3.	There is no null values and duplicate values.

4.	From the line plot we get to see that after 2018 fraud case involving Rana Kapoor it results in very low prices of shares.

5.	To overcome the problem of positively skewed distribution, we have used Log Transformation method.

6.	We have used a heat map plot to get to know the correlation between Dependent and Independent variables. 

7.	Dependent Feature “Close” is completely dependent on Independent features “Open”,  ”High”, ”Low”.

Final Conclusion:-  
1.	We apply Linear Regression, Lasso Regression, Ridge Regression and Elastic Net Regression on our dataset we get to know that Linear and Ridge Regression giving same accuracy of 82.28% and 82.22% and Lasso Regression giving the accuracy score of 81.72% but Elastic Net Regression give the least accuracy of 79.48%.

2.	Linear Regression, Lasso Regression and Ridge Regression gave almost same accuracy into the range of 81% to 83%.


3.	Elastic Net Regression was the one who give least accuracy score of 79.48% only.













