# Power Outage Classification

Whenever there is a power outage, one of the big questions is what caused it. The goal of this project is to classify the cause of a power outage using the characteristics of the outage and the geographic area in which it occured. What this model can't be used for, however, is identifying an outage's cause before it is repaired. Although this would be helpful, this can't be done since one of our main explanatory variables is the outage's duration.

The model uses a K-nearest neighbor classifier with the target variable being power outage cause. For the evaluation metric I will use the accuracy score (proportion of predictions being correct). 
