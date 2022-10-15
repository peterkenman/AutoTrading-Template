# AutoTrading-Template

Please clearly write your idea.
目的:
本作業以實作交易策略為主，以套件之指標撰寫程式
進行Buy/Sell進行交易，並進行Training Data 資料回測達到最大效益。

方法:
利用移動平均線判斷0050 的收盤價，預測未來可能的趨勢，本次作業使用的是加權移動平均(weighted moving average,WMA)大於簡單移動平均(simple moving average,SMA)為買進;相反如加權平均移動小於簡單移動平均為賣出。

Request Package
Pandas,numpy,plotly,TA-lib

Buy:
WMA(5)>SMA(5) and Change>1.02
Sell:
WMA(5)<SMA(5) and Change<0.98

Data Source:

[training_data.csv](https://github.com/Zong-Yue/AutoTrading-Template/files/9792200/training_data.csv)
[testing_data.csv](https://github.com/Zong-Yue/AutoTrading-Template/files/9792201/testing_data.csv)




