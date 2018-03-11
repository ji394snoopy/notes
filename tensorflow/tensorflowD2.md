## AM  
 1. 應用
     - 情境
     - IMP
 2. 模型
     - 淺層 ML
     - 深層 DL 
        + CNN
        + RNN
 3. 實作
    - TF
![MindMap](https://ithelp.ithome.com.tw/upload/images/20180308/20105427KuOaLIBhzb.png)

#### 底層: 
 -kernal
    + 異質性
    + 分散性
 - new Device 
 - TFserving
 - hadoop

#### API:
  - 訓練: 交談式
  - 預測: weighted (tf/API)
        
#### TF Intro  

##### Low-level-API  
  + tf.func tensor array (存放tensor)
  + tf.func operation
  + functions

##### API Layer
![API Layer](https://ithelp.ithome.com.tw/upload/images/20180308/20105427qaKRxVkDfE.png)
  + High 
    estimeter 估算器  
    >  - mk class/model, 
    >  - has to: 
    >    1. have input(x)
    >    2. be trained
    >    3. specify optimization
    >    4. have cost fn
  + Mid 
    - DataSets 數據集
    - Metric 衡量
    - Minify 簡化

## PM
### low level API
  A. 基本: tensor/op
  B. 組裝: 神經元/ANN(MLP)
  C. 模型: 回歸
  D. 函數: 激勵/損失/優化

## refs 
[單元圖](http://www.asimovinstitute.org/neural-network-zoo/)