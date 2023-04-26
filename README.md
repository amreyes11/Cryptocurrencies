# Cryptocurrencies


OVERVIEW

You and Martha have done your research. You understand what unsupervised learning is used for, how to process data, how to cluster, how to reduce your dimensions, 
and how to reduce the principal components using PCA. It’s time to put all these skills to use by creating an analysis for your clients who are preparing to get 
into the cryptocurrency market.  Martha is a senior manager for the Advisory Services Team at Accountability Accounting, one of your most important clients. 
Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. 
The company, however, is lost in the vast universe of cryptocurrencies. So, they’ve asked you to create a report that includes what cryptocurrencies are on the 
trading market and how they could be grouped to create a classification system for this new investment.

The data Martha will be working with is not ideal, so it will need to be processed to fit the machine learning models. Since there is no known output for what Martha is looking for, she has decided to use unsupervised learning. To group the cryptocurrencies, Martha decided on a clustering algorithm. She’ll use data visualizations to share her findings with the board.

Deliverables:
This new assignment consists of four technical analysis parts. You will submit the following:

Part 1: Preprocessing the Data for PCA
Part 2: Reducing Data Dimensions Using PCA
Part 3: Clustering Cryptocurrencies Using K-means
Part 4: Visualizing Cryptocurrencies Results

Part 1: Preprocessing the Data for PCA 
Using your knowledge of Pandas, you’ll preprocess the dataset in order to perform PCA in Part 2.



Part 2: Reducing Data Dimensions Using PCA 
Using your knowledge of how to apply the Principal Component Analysis (PCA) algorithm, you’ll reduce the dimensions of the X DataFrame to three principal 
components and place these dimensions in a new DataFrame.




Part 3: Clustering Cryptocurrencies Using K-means 
Using your knowledge of the K-means algorithm, you’ll create an elbow curve using hvPlot to find the best value for K from the pcs_df DataFrame 
created in Part 2. Then, you’ll run the K-means algorithm to predict the K clusters for the cryptocurrencies’ data.



Part 4: Visualizing Cryptocurrencies Results 
Using your knowledge of creating scatter plots with Plotly Express and hvplot, you’ll visualize the distinct groups that correspond to the three principal 
components you created in Part 2, then you’ll create a table with all the currently tradable cryptocurrencies using the hvplot.table() function.
