# Credit_Card_Fraud

One of the greatest challenges in fraud, and in general in that area of data science related to catching illegal activities, is that one often is one step behind. The model is trained on past data. If users come up with a totally new way to commit a fraud, it often takes some time to be able to react. By the time one get data about that new fraud strategy and retrain the model, many frauds have been already committed. A way to overcome this is to use unsupervised machine learning, instead of supervised. With
this approach, one doesn't need to have examples of certain fraud patterns in order to make a prediction. Often, this works by looking at the data and identify sudden clusters of unusual activities.

This is the goal of this challenge. We have a dataset of credit card transactions and we have to identify unusual/weird events that have a high chance of being a fraud.

Company XYZ is a major credit card company. It has information about all the transactions that users make with their credit card.

Your boss wants to identify those users that in your dataset never went above the monthly credit card limit. The goal of this is to automatically increase their limit. Can you send him the list of Ids?

On the other hand, she wants you to implement an algorithm that as soon as a user goes above her monthly limit, it triggers an alert so that the user can be notified about that. Build a function that for each day, returns a list of users who went above their credit card monthly limit on that day.

Finally, your boss is very concerned about frauds cause they are a huge cost for credit card companies. She wants you to implement an unsupervised algorithm that returns all transactions that seem unusual and are worth being investigated further.
.
