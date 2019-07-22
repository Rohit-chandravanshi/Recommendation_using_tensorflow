# Recommendation_using_tensorflow
Objective:
 To build a recommender system that will recommend products based on customer id using implicit historical data. 

 About Data:
 This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.
 This dataset can be downloaded from http://archive.ics.uci.edu/ml/datasets/online+retail.

 The dataset itself is an Excel file with the following features:
 InvoiceNo: The invoice number, which is used to uniquely identify each transaction
 StockCode: The code of the purchased item
 Description: The name of the product
 Quantity: The number of times the item is purchased in the transaction
 UnitPrice: Price per item
 CustomerID: The ID of the customer
 Country: The name of the customer's country of the customer


 Approach:
  1) At first we will try traditional method of most frequent items that have been bought by customers and recommend them on the basis of this baseline.  
  2)In the third method we will use implicit feedback data of user to produce recommendation using alternating least square method.  
  3) After that we will try  matrix factorization method which is SGD based.  
  4) In fourth step we will convert recommendation problem into a binary classsification so that we can apply a SGD based model on tensorflow.
  5) Then we will improve our results using Bayesian Personalised ranking.
  6) At last we will build RNN model along with LSTM cells to build a reccommender sytem using Tensorflow.
