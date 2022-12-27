# Marketing Strategy
 
**Business Problem**: Based on the personalized offers given in the past and whether the customer accepted the offer or not, suggest some new offers whether that person will accept the offer or not on the basis of different parameters to be decided.The data is collected through a survey to understand the driver's behavior regarding their preference for discount/offer for dining/takeaway. The researcher collected these data by providing different scenarios to various users.

**Approach**:  The Data Set contained the data of whether the offer was accepted or not , the parameters like his age, demographics, the distance from the location where offer was obtained. The data sets were pre-processed in the required format to be fed into the model. The categorical variables were one hot encoded and the the ordinal variables were converted by ranking system to requried numerical number. The missing value treatment was done. Mode was used for categorical variables and average of the column for continous and discrete variables. The Data was then divided into the train and test data sets. The training dataset was then fed into different models to test for the best model. The best model was then tuned to its best parameters using Hyper parameter tuning technique grid search cv. Also the model was then trained on to achieve 70 % F1 Score on test data and 60 % on unknow random dataset.

**Improvements Possible**: More Data on the customers requried for improving the model. Also going into deep learning could increase the scoring.
