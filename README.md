# Online Retail store: Customer Segmentation

[Check out the detailed report and source code](https://github.com/DataSorcerer/Retail-Customer-Segmentation/blob/master/Retail_Analytics_report_source_code.ipynb)     

We endeavour to find the various customer segments using the online retail store's transaction data obtained from [UCI Machine Learning Dataset repository](http://archive.ics.uci.edu/ml/datasets/online+retail). This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.

### The need of customer segmentation:   
The differences in customers' behaviour, demographics, geographies, etc. help in classifying them in groups. Learning about different groups in the customer can help with following:    

1. Target Marketing    
2. Client understanding
3. Optimal product placement
4. Searching for new customers
5. Revenue growth   


### Recency-Frequency-Monetary <font color=blue>(RFM) </font> model to determine customer value:    

The RFM model is quite useful model in retail customer segmentation where only the data of customer transaction is available. RFM stands for the three dimensions:

 - *Recency* – How recently did the customer purchase?
 - *Frequency* – How often do they purchase?
 - *Monetary Value* – How much do they spend?    
 

A combination of these three attributes can be defined to assign a quantitative value to customers. e.g. A customer who recently bought high value products and transacts regularly is a high value customer. 

### Segmentation with K-means clustering:    

- Initially, the data is subject to important stages in an analytics pipeline: exploratory analysis, preprocessing, feature engineering and standardizaton.    
- Then, the unsupervised classification technique, K-means clustering algorithm, is used to determine the ideal segments of customers. Silhouette analysis and related cluster visualizations are leveraged to deduce the optimum value of "K" (number of clusters) in the algorithm.       
- The observations from the results are elaborately discussed before reaching the conclusion from the business perspective.
