# Stocktwits -- real-time sentiment analysis
![Screenshot](https://github.com/NYU-CS6313-SPRING2016/Group-5-StockTweets/blob/master/Screen%20Shot%202016-08-22%20at%208.31.35%20PM.png)
- Video: https://vimeo.com/167449385
- Final Document: https://prezi.com/xza6pce6qwmm/stocktwits-dashboard/ 
- Working demo: [STOCKTWITS.com](http://angelinazhao.com/stock/)

####Description
Our project aims to develop a visual analytic platform to mine and visualize data to facilitate diverse traders to make decisions, specifically to buy or to sell. In our project, we hope traders can get information from the website, explore how the stock market is moving and make better decisions. We want to help users filter and visualize the tweets data so that they can understand the activities and market consensus of the stocks they are watching. In addition, they should also be able to capture the credibility and real-time data visualization by overview monitoring of the stock market. We need to pull data in sections like trending, investor-relation to give a further and concise analysis and visualization in aspects of the average recommendation, the market trending and the company/trader credibility and so on.

####We hope to deal with the following question
- 1.	How does the whole market change?
- 2.	What is the top hot sectors or stocks on the StockTwits?
- 3.	What is the co-relation between the stocks and the changes of their market mood?
- 4.	What kinds of traders are talking about the stock? What are their attitudes?
- 
##Data Source
- [StockTwits API](http://stocktwits.com/developers)
- [Yahoo Finance API](https://pypi.python.org/pypi/yahoo-finance/1.1.4)

##Install Instructions
###Requirements
The systems has the following dependences:

1. **Python**: 2.7
2. **Heroku**

###Runing
You may directly visit our online website. If you want to run it locally, you can clone the repository by:
```sh
https://github.com/NYU-CS6313-SPRING2016/Group-5-StockTweets.git
```


1. Run the server for local test:

	```sh
		$ cd Group-5-StockTweets
		$ python stocktwitsFinal.py --num_twits 50
		$ python stock_price.py --symbol_file maxsymbol.json
		$ python -m SimpleHTTPServer 8000
	```

2. Then access to:

	```sh
		 `localhost:8000/stocktwits`
	```
