# Project_work
### Team Members:
##### 1. Rajat Kumar
##### 2. Usha Devi
##### 3. Khushboo Tiwari
##### 4. Rajani Singh
### Objective of Project  
Predict the next 30 day closing price of Nifty

## We Use:
### Type of Data: Panel Data or Longitudinal Data
### Data: Past 5 Year Nifty  data    
### Software: Python,R  

## Meeting 1:  
### Question to be answered: -  
Q1. How daily Nifty is calculated?  
Ans. Nifty 50 is calculated by taking the weighted value of the 50 stocks listed on NSE and is based on free-float market capitalisation. The index value is calculated using market capitalisation and reflects the value of the stocks relative to the base period. The market value is calculated as the product of several shares and the market price per share.  

Index value = Current market value / (Base Market Capital * Base Index Value)  
As the value of Nifty is based on weighted cost, the companies with more massive stocks affect the value more than the companies with smaller capital.  

Q2. How can we forcast the index?  
Ans. There are multiple ways to predict market for the next day using charts or NSE data. One can see Time Cycle in conjunction with Wave Analysis like Neo or Elliott waves or we can use Indicators like Ichimoku and RSI/ROC or simple Price Action can also tell you market Direction. Some also use OI data to predict market.  
Some use Machine Learning and Predictive Models like ANN, Prophet etc. to forecast the index of Nifty.  


Q3. Characterstic of stock index.  
Ans. Stock index futures have the following characteristics:

 

(1) Spread. Stock index futures are contracts to be traded based on certain conditions at a certain time in the future stipulated by the two parties of the transaction according to the prediction of the stock index movements. Therefore, stock index futures trading is based on predictions. Whether the investors will make a profit or suffer a loss is directly determined by the accuracy of the prediction.  

 

(2) Leverage. Investors can sign contracts with large value by paying a certain percentage of funds as the guarantee for performance instead of paying the contract value in full amount in the process of stock index futures trading. For example, assuming the margin in the stock index futures trading is 12%, investors can conduct the trading by paying the fund of 10% of the contract value. In this way, investors can dominate the contract assets 8 times the invested fund. Of course, the loss that might be undertaken by investors will also be multiple as the income might be multiple.  

 

(3) Linkage. Stock index futures price is closely linked with the change of the underlying asset, that is, the stock index. Stock index, the underlying asset of stock index futures, has great influence on change of stock index futures price. In the meanwhile, stock index futures reflect the stock index to some extend as they are predictions of the future prices.  

 

(4) High risk and diversity of the risk. Stock index futures’ characteristic of being the leverage determines that their risk is higher than that of the stock market. In addition, there are credit risk, settlement risk and liquidity risk stemming from a close position due to the lack of counterparty on the market in stock index futures.  

Are the models are really appropriate for data?  


Forcasting for such a long time (1 month) is feasable?  

#### For this forcasting we use "knn", "Prophet", "GARCH" and "ARIMA" model  


