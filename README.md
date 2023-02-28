# Assignment-1-SDSC3002
I used "apyori" library with its pre-installed apriori algorithm to run through the transaction data.
I loaded the necessary libraries such as numpy and pandas.
The proceeded to data preprocessing. I read the data using pd.read_csv, then changed the delimeter from tab to semicolon.
Instead of dataframe, I arranged the data in the form of numpy array. 
Once that was done, the code was ready to run through Apriori algorithm. 
I varied values of min_support from 0.0001 to 0.0005. The code took quite long to execute. However, the results seemed quite accurate in terms of the total number of transactions for each varied min_support.
