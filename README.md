# tffactorization
Implementations of matrix factorization or tensor factorization algorithms on TensorFlow

This contains here:
        Non-negative Matrix Factorization

#Basic Usage
When applying NMF for V=WH,
```
import tensorflow as tf
from tfnmf import TFNMF

tfnmf = TFNMF(V, rank)
with tf.Session() as sess:
    W, H = tfnmf.run(sess)
```
