solve classification problem using probabilistic generative model steps (*[[Framework of ML]]*):
1. Function Set: 定義機率函數，找出x是各種class的機率
2. Goodness of a function: 判斷function符合class分布的情形
3. Find the best function: Maximizing Likelihood
![[Pasted image 20230702195710.png]]

運用貝氏定理，定義給定一個sample x，是class C1的機率P(C1|x)
![[Pasted image 20230702195224.png]]

假設class分布的情況，這裡使用[[Gaussian Distribution]] (最常見)
![[Pasted image 20230702195345.png]]

### Maximizing Likelihood
找到最符合class分布情況的function -> mean & covariance matrix
![[Pasted image 20230702195456.png]]
![[Pasted image 20230702201714.png]]

接著便能進行classification
![[Pasted image 20230702195600.png]]


### Optimization
不同feature使用相同的covariance matrix (簡化參數) -> class boundary becomes linear
![[Pasted image 20230702195641.png]]
![[Pasted image 20230702195654.png]]

