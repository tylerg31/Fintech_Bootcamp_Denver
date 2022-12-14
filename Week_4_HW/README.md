#README

In this assignment we compared several large funds ("whales") to the performance of the SP500 and assessed their invement merits by looking at their
risk adjusted returns.  To complete this exercise we used the pandas and numpy libraries to work with our data set. 

We first took the closing values of the funds and index and converted those into daily returns. Then we summed the daily returns to find the total returns.
But cumulative return does not give us insight into the riskiness of the portfolio. For more in depth analysis we needed to look at the risk adjusted   
returns. To do this we found the daily standard deviation and then the annual standard deviation. Now that we have a measure of risk we used this value
in combination with the returns of each to find the Sharpe ratio, which is a measure of return per unit of investment risk. 

Finally we took the variance and covariance of the funds and the index and used these terms to find our beta for each fund. Beta is a measure of a funds  
sensitivity to the movement of the index. 

We were able to determine that the Berkshire Hathaway fund was the most likely candidate for inclusion in our portfolio. While not returning as much as the
SP500, the Berkshire fund maximized its returns per unit of risk compared to the other funds in the analysis. 
