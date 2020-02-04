# 100Numpy题
## 1.sum函数
* python自带的sum函数是 sum(iterable[, start])，第二个参数默认为0，可以加在一起

* Numpy中的sum函数中第二个参数表示维度，也就是其求和的方向
```Python
numpy.sum(a,
          axis=None,
          dtype=None,
          out=None,
          keepdims=<class 'numpy._globals._NoValue'>)
```