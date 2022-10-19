# MLDS HW1 - AutoTrading
Editer:鄭信乙 楊宗岳
ID:N27101081
Date:2022.10.16

# Evaluation Goal
Maximize the profit you gain. 
We will use one month's data as the test data set.
Please aim to maximize revenue in 20 days.

Input Data:
training_data=>
testing_data=>

Output Data:
"output.csv"

Action Type:
1:Buy 0:NoA

# Environment

# 利用循環神經網路(recurrent neural network,RNN) 實作預測
1.首先讀入trainning_data 並觀察資料型態及欄位。
2.資料前處理Preprocessing,=>Max-Min Normalize 透過數據標準化並將數據按比例縮放0~1的區間值。(提升精準度及梯度下降)
3.預測收盤價
