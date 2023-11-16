# Stock Data Analysis
近20年股票交易数据获取，指标数据获取，明日价格预测。  

## 股票基础信息获取
http://124.221.247.48:5000/api/v1.0/stock

## 股票交易数据获取
http://124.221.247.48:5000/api/v1.0/data?symbol=000001&begin=2023-11-14&end=2023-11-14

![image](https://github.com/limengmeng2024/StockDataAnalysis/assets/151038602/adf0fb80-7d50-4a09-a8a7-2418b15cf47e)

## 股票明日价格预测数据获取
http://124.221.247.48:5000/api/v1.0/guess?symbol=000001

![image](https://github.com/limengmeng2024/StockDataAnalysis/assets/151038602/502ce4b4-8f4f-4f31-93ae-cbc8feded162)


## 股票指标数据获取
http://124.221.247.48:5000/api/v1.0/indicator?symbol=000561&begin=2023-9-1&end=2023-10-15&type=Macd

其中指标类型支持如下：
Wma  
ZigZag  
Condense  
StarcBands  
Stoch  
StochRsi  
SuperTrend  
T3  
Tema  
Tr  
Trix  
Tsi  
UlcerIndex  
Ultimate  
VolatilityStop  
Vortex  
Vwap  
Vwma  
WilliamsR  
Roc  
RocWb  
RollingPivots  
Rsi  
Slope  
Sma  
SmaAnalysis  
Smi  
Smma   
Stc   
StdDev  
StdDevChannels  
Mama  
Marubozu   
Mfi   
Obv  
ParabolicSar   
PivotPoints   
Pivots   
Pmo   
Prs   
Pvo   
Renko   
RenkoAtr   
ForceIndex   
Fractal  
Gator   
HeikinAshi   
ToQuotes   
Hma   
HtTrendline  
Hurst  
Ichimoku  
Kama  
Keltner  
Kvo   
Macd   
MaEnvelopes   
Cmo   
ConnorsRsi   
Correlation   
Dema   
Doji   
Donchian   
Dpo   
Dynamic   
ElderRay   
Ema   
Epma   
Fcb   
FisherTransform   
Adl   
Adx   
Alligator   
Alma    
Aroon   
Atr   
AtrStop   
Awesome   
BaseQuote  
Beta   
BollingerBands   
Bop   
Cci  
ChaikinOsc  
Chandelier  
Chop   
Cmf   

# 注意事项
每天单个IP最多请求500次，超过该值访问将被拒绝，请注意。如需了解更多，请关注微信公众号。    

![qrcode_for_gh_4a654e9b844e_258](https://github.com/limengmeng2024/StockDataAnalysis/assets/151038602/504d46cb-4e75-4539-9674-5227da618eb6)
