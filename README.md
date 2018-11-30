# MARKET BUCKET ANALYSIS AND SEQUENCE ANALYSIS in R
### METHODOLOGY
The code is writen in R. The html files in the folders is the R NOTEBOOK of the implementation.

### Dataset
The dataset was provided by an e-commence website (ie. YOOCHOOSE) for the RecSys 2015 Challenge. The dataset consists of 
a collection of sequences of click events and sessions. There are also buying events for some of the sessions. Hence, based 
on these two datasets, goal is to predict what a user will buy given what the user had bought using association and 
sequences analysis. 

### Challenges
The main challenge of the task is to handle the large amount of data on hand. Pre-processing steps include cleaning and 
transforming the data so that it fits the model in pattern discovery. Apriori algorithm was used to find the association rules 
and CSAPDE algorithm was used for sequences analysis.

### Market Basket Analysis
Market Basket Analysis help e-retailers uncovered association between items. It looks for combination of items that occur 
together frequently in transactions to allow retailer to identify relationship between the items the customers buy. 
This also assist the retailer to recommend the next page or item for the customers to view.
Apriori algorithm was used to perform Association/ Market Basket Analysis to uncovered association between items. 

### Sequence Analysis 
Previously we had extracted association rules based on the strong association between the item bought in a market basket. 
The information allows the e-retailer to make recommend to the user based on the shopping cart items bought or selected. 
Next is to find out what a user will buy next given a previous item bought. The sequence of the purchase is therefore important.
The sequence of the purchase is important in frequent sequence mining. CSPADE Algorithm will be used to find the set of patterns 
shared among the items which were specifically ordered according to the date and time. 
