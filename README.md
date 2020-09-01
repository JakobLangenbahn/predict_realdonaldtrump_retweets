#  Predicting Retweets of @realDonaldTrump Twitter account.

## Abstract

There are few topics that polarize as much as Donald Trump's tweets. This project explores the question of which factors contribute to the fact that a tweet is retweeted particularly often. Based on Donald Trump's tweets since his inauguration, different regression models were implemented to predict the amount of retweets and the results were interpreted using SHAP values. The final model is a random forest witha RMSE of 11,253 on the test set. It seems like the variables number of mentions, including of urls, month of creation, text length and a few special words have a particular high influence on the retweet count.


## Potential improvements:
* Mine data directly from twitter
* Improve feature generation
* Improve model
* Improve explainability
* Implement a dashboard for predicting the number of retweets of a new tweet
