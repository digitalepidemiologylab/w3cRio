Each csv contains the logit of the frequencies of each of the 1000 most common keywords in the dataset and the logit of the CDC's reported ILI rate for that week. The rows are in order based on time, where the first week is the 40th week of 2011 (see paper). In the regional datasets, the rows are ordered such that the first 34 are for region 1, then the next 34 are for region 2, and so on.


The top keywords were estimated by Apache Hive's ngram function. Because they are estimates, the ranking may be slightly off. 
