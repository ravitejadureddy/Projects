# LTFS

This project is based on Analytics Hackathon-LTFS2. Here, the L&T company challenges the individuals to predict the number of loan applications they receive each day, so that they can accomodate enough resources to process the cases in less time and improve their customer satisfaction.
For this business use case, L&T has provided the number of applications they have received earlier, requesting them for loans for 2 of their business segments.

The link to this challenge can be found below:
https://datahack.analyticsvidhya.com/contest/ltfs-data-science-finhack-2-an-online-hackathon/

The Training Data(historical data) has been attached in the repository, along with Test Data for which the predictions need to be made.
The files that include the Festivals, Inflation Rate etc., can also be found in the repository.

Here, I performed activities of Data Loading, Transformation, Data Exploration, Feature Engineering for developing the Data required for macking the predictions.
Upon Data Exploration, I came to know that the data set has many data points and good number of columns for building effective models. So, I used MLP Regressor, Random Forests and XGB regressor algorithms for Model Building phase.

Finding optimal hyperparameters for these models was a challenge. Using GridSearchCV for finding optimal hyper parameter combination in each of these models and estimating the performance of the best estimators from each family of models, by evaluating through Validation Set was performed.
From this process, i found the best estimator for segment1 as MLP regressor and for Segment2 it is XGB Regressor. I used these regressors over the test data and loaded the number of applications that will be received on the required dates into CSV file(attached).
