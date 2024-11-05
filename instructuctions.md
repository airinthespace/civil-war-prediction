We have provided you with a dataset called `civil_wars.RData`, which records for each country and every year, whether that country was engaged in a civil war. The data was taken from Kaufman et al’s (2019) replication materials, which focuses on the use of boosted decision trees:

*Kaufman AR, Kraft P, Sen M. Improving Supreme Court Forecasting Using Boosted Decision Trees. Political Analysis. 2019;27(3):381-387. doi:10.1017/pan.2018.59*

To read this dataset you need to call `load(civil_wars.RData)`, which will load the data as a variable called `civwars` into your environment. When you view the data in R (i.e. `View(civwars)`), you will see the variable descriptions under the variable names. We have removed country names from the dataset intentionally, so that all variables are numerical, and imputed any missing values.

Your task is to build a model to predict civil war. You should use the data however you see fit, and you may use any class of model we have considered (including any already covered in this assignment).

Your answer should be a report of between 250-500 words that a) introduces the problem, b) summarises any decisions you made about training the model, and c) demonstrate your final trained model’s performance. You may use (well-formatted) charts to help illustrate your claims.

*Note*: you do not need to submit the trained model object, and may use any R packages/functions in this task.

