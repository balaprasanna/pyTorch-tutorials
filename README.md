## Welcome to pyTorch Tutorial
This is my weekend exploration of pyTorch.

#### Exercise 1
![First equation](http://latex.codecogs.com/gif.latex?loss%28w%29%3D%5Cfrac%7B1%7D%7BN%7D%5Csum_%7Bn%3D1%7D%5E%7BN%7D%28%20%5Chat%7By%7D_%7Bn%7D%20-%20y_%7Bn%7D%20%29%5E%7B2%7D)

<!---
loss(w)=\frac{1}{N}\sum_{n=1}^{N}( \hat{y}_{n} - y_{n} ))
-->

#### List of formula 

![Loss](http://latex.codecogs.com/gif.latex?loss%3D%28%20%5Chat%7By%7D%20-%20y%20%29%5E%7B2%7D%3D%28x%20*%20w%20-%20y%29%5E%7B2%7D%29)

<!--- loss=( \hat{y} - y )^{2}=(x * w - y)^{2})  -->
<!---  -->

![Yhat](http://latex.codecogs.com/gif.latex?%5Chat%7By%7D%3D%28x%20*%20w%29)

<!---  \hat{y}=(x * w) -->

Now we need to find w which minimizes the loss
```
argmin loss(w)
```
