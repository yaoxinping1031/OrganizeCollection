# 备注

## arima-lstm
结合了自回归移动平均（ARIMA）模型和长短时记忆网络（LSTM）模型。  
1.ARIMA模型： 首先，使用ARIMA模型对时间序列数据进行建模和预测。ARIMA模型是一种经典的时间序列分析方法，它考虑了时间序列数据的自回归（AR）和移动平均（MA）成分。通过ARIMA，可以获得初始的时间序列预测结果，包括趋势、季节性和残差。  
2.LSTM模型： 然后使用LSTM模型进一步改进ARIMA的预测。LSTM是一种深度学习模型，专门用于处理序列数据。将ARIMA模型的残差作为输入，通过LSTM模型来学习和捕捉更复杂的序列模式和动态。LSTM可以自动地考虑不同时间步之间的关系和依赖性。  
3.组合预测结果： ARIMA和LSTM模型各自生成了预测结果，将它们组合在一起以获得最终的预测结果。通常，你会将ARIMA模型的预测结果与LSTM模型的预测结果相加或进行其他合并操作。

其余算法可考虑：
1）CNN  
2）CNN-LSTM(复合算法)  
3）LSTM （有）
4）TCN  
5）GRU  
6）ARIMA （有） 
7）ARIMA-LSTM(复合算法)  （有）
8）TCN-LSTM(复合算法)  
9）TCN-Attention(复合算法)  
10）LSTM-Attention(复合算法)  
11）TCN-GRU(复合算法)  
12）informer  
13）transformer  
14）cnn-lstm-Attention(复合算法)  
15）VMD-LSTM/EMD-LSTM(预处理算法)  
