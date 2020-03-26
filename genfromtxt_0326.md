
# NumPy (N-Dimensional Arrays)

## NumPy ndarray

是一個快速的且可以節省空間的多維度陣列，提供向量運算以及複雜的功能



## numpy(array)
```
#匯入函式庫
import numpy as np

ar2=np.array([[0,3,5],[2,8,7],[3,3,3],[2,2,2]]) # 2D array
#印出陣列資料
print(ar2.shape)
##印出ar2的維度數量(ar2為二維陣列)
print(ar2.ndim)
```

## numpy(dtype,astype)

dtype是在建立資料式同時指定資料型態(使用np.dtype可查詢物件的type)，astype可之後修改資料型態

```
ar=np.array([2,4,6,8]); 
ar.dtype
```
