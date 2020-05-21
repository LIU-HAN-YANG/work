讀取影像使用 cv2.imread()，該函數支援各種靜態影像

```
# -*- coding: utf-8 -*-


import cv2

lena=cv2.imread("lena.bmp")
r=cv2.imwrite("result.bmp",lena)
type(lena)
lena.shape

```
```
import cv2

lena=cv2.imread("lena.bmp")
cv2.namedWindow("lesson")
cv2.imshow("lesson", lena )

```
```
import cv2

lena=cv2.imread("lena.bmp")
cv2.imshow("demo", lena )
key=cv2.waitKey()
if key==ord('a'):
    cv2.imshow("PressA",lena)
elif key==ord('b'):
    cv2.imshow("PressB",lena)

```
```

```
