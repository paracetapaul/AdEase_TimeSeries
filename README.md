# AdEase_TimeSeries

From the company’s perspective:
● Ad Ease is an ads and marketing-based company helping businesses elicit
maximum clicks @ minimum cost.
● AdEase is an ad infrastructure to help businesses promote themselves easily,
effectively, and economically
● Ad ease trying to understand the per page view report for different wikipedia
pages for 550 days, and forecasting the number of views so that you can predict
and optimize the ad placement for your clients.
● By leveraging data science and time series, Ad Ease can forecast page visits for
different languages.

DataSet Explanation
There are two csv files given
1. train_1.csv : In the csv file, each row corresponds to a particular article and each
column corresponds to a particular date. The values are the number of visits on that
date.
The page name contains data in this format:
SPECIFIC NAME _ LANGUAGE.wikipedia.org _ ACCESS TYPE _ ACCESS ORIGIN
having information about page name, the main domain, device type used to access the
page, and also the request origin(spider or browser agent)

2. Exog_Campaign_eng: This file contains data for the dates which had a campaign or
significant event that could affect the views for that day. The data is just for pages in
english.
There’s 1 for dates with campaigns and 0 for remaining dates. It is to be treated as an
exogenous variable for models when training and forecasting data for pages in english

What is Expected?
You are working in the Data Science team of Ad ease trying to understand the per page
view report for different wikipedia pages for 550 days, and forecasting the number of
views so that you can predict and optimize the ad placement for your clients. You are
provided with the data of 145k wikipedia pages and daily view count for each of them.
Your clients belong to different regions and need data on how their ads will perform on
pages in different languages.
