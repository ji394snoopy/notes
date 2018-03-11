
## AM
### 模型(演算法/網路):
  1. ML(Machine Learning)
  2. DL(Deep Learning)
  3. 單一神經元
  4. 複合DL (Basic cell)
  5. 結構(結構化神經元)
### 應用:
  1. Vision:
      - Detect + Rec + Query
      - Image Caption
  2. NLP(時序):
      - MLP/NNLM/對話
      - 知識圖層
      - 強化學習

#### DL (二階段)  
  + 學習: 特徵 (權重、超參數)  
  + 應用

##### 訓練: 訓練超參數得到精準的權重，每個叉路所得到的數據  
算出中間層的參數是否正確: 
> 輸入 => 輸出 (前向) 

## PM
### 思路  
1. 模型(建構):
    -  單一perception
    -  ANN(人工神經網路)
    -  多層(MLP)
2. 總目標:
    -  反向(backProgation) => find weight
    -  函數、泛化
3. 實作:
    -  Tensor Flow
    
### 神經  
[過程](https://pic.pimg.tw/darren1231/1483983047-2197600735.png?v=1483983068)
*inputs(X)*Weights* `ex. {x1*w1: '帥', x2*w2: '哥' }` => 
*sum* (+b彈性) => 
*f(x) 激勵函數(mapping)* ex. `f(x):{ x<0 || 1, x>=0 || x}` => 
*output(y)* 
> 神經: 加總 then 映射

損失函數: 結果可接受的偏差

#### 單一P
  1. 蒐集Sample
      > Attributes (domain problem)
      > Y (answer)
     + Training Set(80%) 準、確、泛化(可以舉一反三) 
     + Test Set(20%)
  2. 建構網路模型
      > 越簡單越好
      > 參考arXiv論文+github
     + 線性可分
     + 針對一個世代訓練 (init weight)    

#### TensorFlow  
> TF Family
> 1. TensorFlow Framework
> 2. TensorBoard 圖形化流程(Graph)
> 3. TensorDebugger(Dynamic)
> 4. TensorServing(Deploy)

using concept:  
  1. Graph(model)
  2. Session(environment config: pc, mobile, gpu, cpu...)

tf concept:  
1. varibles TFX -> Python `x = [28, 28, 1] (28\*28(10))`
2. tensor(張量) `tf.fn([28, 28, 1])`
3. build: tenser\<placeholder\>


## refs 
[單元圖](http://www.asimovinstitute.org/neural-network-zoo/)
[類神經網路 筆記](http://darren1231.pixnet.net/blog/post/338810666-%E9%A1%9E%E7%A5%9E%E7%B6%93%E7%B6%B2%E8%B7%AF%28backpropagation%29-%E7%AD%86%E8%A8%98)
[arXiv](https://arxiv.org/)
