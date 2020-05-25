# App: When Should You Refinance?

## Team Members: Joseph, Justin, Kip, Scott, Sean

## Project Description/Outline: 
Idea is to create an app that allows user interaction in which the user provides their information related to refinancing a mortgage (location, credit score, amount, years remaining, etc), and the output is a calendar showing likely rates that would be offered over the next X number of weeks, along with actionable "This is the likely week you should re-finance". Behind the scenes, the app uses machine learning to predict what interest rate the user would be offered based on their answers to the app's questions.

## Datasets to Be Used
1. Fannie Mae [Single Family Home Loan Performance dataset](https://www.fanniemae.com/portal/funding-the-market/data/loan-performance-data.html)
2. New York Fed [average interest rates by quarter](https://www.newyorkfed.org/microeconomics/hhdc/background.html) - Excel file
3. myFICO [current today's average mortgage rate for various credit scores](https://www.myfico.com/loan-center/home-mortgage-rate-comparison/default.aspx)

## Possible Scope Creep
1. Comparing 2008 mortgage/housing data to today
2. Normal vs. outlier data

## Rough Breakdown of Tasks
1. Scott - web scraper for myFICO, identify additional options
2. Sean - d3, Bootstrap, website
3. Kip - Validate Fannie Mae dataset; explore Fannie Mae dataset
4. Joseph - EDA on Fannie Mae dataset?
5. Justin - EDA on Fannie Mae dataset?

## Suggestions for models
1. Pick apart the dataset to find the features that are most correlated
2. For the top variables, do we have skew or normal distribution?
3. For the top variables, what segmentation do you see (if any)?
