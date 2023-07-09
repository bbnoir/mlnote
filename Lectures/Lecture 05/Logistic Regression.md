在classification中，可以直接找sigmoid function的參數w和b -> 接近(Linear) [[Regression]]
based on: [[Posterior Probability - Sigmoid function]]

![[Pasted image 20230709185535.png]]

1. Function set: 變數為sigmoid的參數wi和b
![[Pasted image 20230709185504.png]]

2. Goodness of a function: cross entropy between class & function result
*[[Why not square error]]
![[Pasted image 20230709185901.png]]

3. Find the best function: after differentiation, we find the same result as linear regression
*[[Derivation of logistic regression differentiation]]*
![[Pasted image 20230709190842.png]]

Better than Lec4 [[Classification-Probabilistic Generative Model]]
-> [[Classification--Generative vs Discriminative]]

### [[Limitation of Logistic Regression]]
