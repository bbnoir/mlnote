the method to find the min loss for regression

### Method
1. Pick an initial value w0
2. Find gradient of loss function on w0
3. Get next value w1 by the formula below
![[Pasted image 20230629175451.png]]

### Cons
+ stuck where of zero gradient (local min, saddle)
+ very slow at the plateau

### Optimization Tips
+ [[Tuning your learning rates]]
+ [[Stochastic Gradient Descent]]
+ [[Feature Scaling]]

### Math
[[Derivation for Gradient Descent]]


![[Pasted image 20230625191937.png]]
![[Pasted image 20230625192624.png]]
