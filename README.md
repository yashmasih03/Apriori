# Movie-Recommendation-System

This is an implementation of Apriori Algorithm using Python.
Here we have used python libraries like pandas,mlxtend

The algorithm of the code is as follows:
1. First we will import the libraries and the two dataset files Movies.tsv, ratings.tsv.
2. Then we are going to create a mapping between movieId and title.
3. We will now sort the highrated movies > 4 ratings .
4. We will perform data preprocessing converting the transactions to a binary representation by using TransactionEncoder from mlextend.preprocessing. If an item is present in the transaction, it will be tagged as 1 ,otherwise 0.
5. Now by using the apriori algorithm we will find the optimal solution by min_support=0.2,max_len=2,metric="lift",min_threshold=2
6. Hence we get the result as ancedents -> consequents


reference site:  https://levelup.gitconnected.com/create-a-recommendation-system-in-python-d7a95b2837ab
