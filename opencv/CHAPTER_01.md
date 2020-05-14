
```
import tensorflow as tf
c = tf.constant(5)
v = tf.constant(1)
print(c)
#print(v)
print("{} 階Tensor".format(c.ndim))
# scalar(常數就是純量[標量])
```
```
x = tf.constant([1, 2, 3, 4, 5, 6]) 
print("{}階Tensor ".format(x.ndim))
```
```
x = tf.constant([[1, 2, 3], [4, 5, 6]])
print("{}階Tensor ".format(x.ndim))
```

Eager Execution 動態圖 (TF2)
