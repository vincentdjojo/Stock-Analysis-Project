# StockAnalysisProject
Apply data mining to discover patterns regarding stock data. 

Read COMP4433-Project1.pdf to see more on what this project is about.

Software needed:
Anaconda 3
Jupyter Notebook

Instructions:
1. Open indproj2.ipynb using Jupyter Notebook.
2. Have stock-all.csv in the same folder as indproj2.ipynb

OR you could just view indproj2.ipynb on GitHub.

There are several steps that I used to analyse the data. 
I mainly used classification, scatterplots and histograms to get a better understanding of the data and its patterns. 
In this project I will be using SciKit learn which is imported in a Jupyter notebook. 
References: 
• https://towardsdatascience.com/in-12-minutes-stocks-analysis-with-pandas-and-scikit-learn-a8d8a7b50ee7 
• https://towardsdatascience.com/a-beginners-guide-to-linear-regression-in-python-with-scikit-learn-83a8f7ae2b4f 

Here are the steps I used to understand the data:

1.    Describe the dependencies used in the Jupyter notebook.
2.    Collect the data of all the stocks in stock-all.csv.
    a.    Describe the data.
    b.    Transform the data for modelling.
3.    Modelling using Linear Regression.
    a.    Plotting Close vs Date for each stock.
    b.    Plotting the max average closing price.
    c.    Training the data and separating them in train and test for linear regression.
    d.    Compare the predictions from linear regression against the actual data.
    e.    Plotting the linear regression graph.
    f.    Check the rolling mean of the closing prices.
    g.    Check the absolute error, mean squared error and root mean squared error.
    h.    Plotting the moving average of the closing price.
    i.    Explaining Return Deviation and using the Return Deviation graph to check whether you the stock is stable and profitable.
4.    Analysing the provided stocks against each other.
    a.    Correlation analysis.
    b.    Stocks Returns Rate and Risk.
