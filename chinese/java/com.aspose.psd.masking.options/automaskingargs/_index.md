---
title: "AutoMaskingArgs"
second_title: "Aspose.PSD 的 Java API 参考"
description: "表示为自动掩码方法指定的参数"
type: docs
weight: 11
url: /zh/java/com.aspose.psd.masking.options/automaskingargs/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.masking.options.IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs)
```
public class AutoMaskingArgs implements IMaskingArgs
```

表示为自动掩码方法指定的参数
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AutoMaskingArgs()](#AutoMaskingArgs--) |  |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMaxIterationNumber()](#getMaxIterationNumber--) | 获取最大迭代次数。 |
| [getNumberOfObjects()](#getNumberOfObjects--) | 获取要将初始图像分离为的对象数量（可选），默认值为 2（对象和背景）。 |
| [getObjectsPoints()](#getObjectsPoints--) | 获取属于分离对象的点（可选）NumberOfObjects 坐标，这些坐标属于初始图像的 NumberOfObjects 对象。 |
| [getObjectsRectangles()](#getObjectsRectangles--) | 获取属于分离对象的对象矩形（可选）。 |
| [getOrphanedPoints()](#getOrphanedPoints--) | 获取不再属于任何对象的点（可选）。 |
| [getPrecision()](#getPrecision--) | 获取分割方法的精度（可选）。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxIterationNumber(int value)](#setMaxIterationNumber-int-) | 设置最大迭代次数。 |
| [setNumberOfObjects(int value)](#setNumberOfObjects-int-) | 设置要将初始图像分离为的对象数量（可选），默认值为 2（对象和背景）。 |
| [setObjectsPoints(Point[][] value)](#setObjectsPoints-com.aspose.psd.Point-----) | 设置属于分离对象的点（可选）NumberOfObjects 坐标，这些坐标属于初始图像的 NumberOfObjects 对象。 |
| [setObjectsRectangles(Rectangle[] value)](#setObjectsRectangles-com.aspose.psd.Rectangle---) | 设置属于分离对象的对象矩形（可选）。 |
| [setOrphanedPoints(Point[] value)](#setOrphanedPoints-com.aspose.psd.Point---) | 设置不再属于任何对象的点（可选）。 |
| [setPrecision(double value)](#setPrecision-double-) | 设置分割方法的精度（可选）。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingArgs() {#AutoMaskingArgs--}
```
public AutoMaskingArgs()
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMaxIterationNumber() {#getMaxIterationNumber--}
```
public final int getMaxIterationNumber()
```


获取最大迭代次数。

值：最大最大迭代次数。

**Returns:**
int - 最大迭代次数。
### getNumberOfObjects() {#getNumberOfObjects--}
```
public final int getNumberOfObjects()
```


获取要将初始图像分离为的对象数量（可选），默认值为 2（对象和背景）。

值：对象的数量。

**Returns:**
int - 将初始图像分割为的对象数量（可选），默认值为 2（对象和背景）。
### getObjectsPoints() {#getObjectsPoints--}
```
public final Point[][] getObjectsPoints()
```


获取属于分离对象的点（可选）NumberOfObjects 坐标，这些坐标属于初始图像的 NumberOfObjects 个对象。此参数用于提高分割方法的精度。

值：对象的点。

**Returns:**
com.aspose.psd.Point[][] - 属于分离对象的点（可选）NumberOfObjects 坐标，这些坐标属于初始图像的 NumberOfObjects 个对象。
### getObjectsRectangles() {#getObjectsRectangles--}
```
public final Rectangle[] getObjectsRectangles()
```


获取属于分离对象的对象矩形（可选）。此参数用于提高分割方法的精度。

值：对象的矩形。

**Returns:**
com.aspose.psd.Rectangle[] - 属于分离对象的对象矩形（可选）。
### getOrphanedPoints() {#getOrphanedPoints--}
```
public final Point[] getOrphanedPoints()
```


获取不再属于任何对象的点（可选）。此参数仅在重新分割的情况下使用。

值：孤立的点。

**Returns:**
com.aspose.psd.Point[] - 不再属于任何对象的点（可选）。
### getPrecision() {#getPrecision--}
```
public final double getPrecision()
```


获取分割方法的精度（可选）。

值：分割方法的精度（可选）。

**Returns:**
double - 分割方法的精度（可选）。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setMaxIterationNumber(int value) {#setMaxIterationNumber-int-}
```
public final void setMaxIterationNumber(int value)
```


设置最大迭代次数。

值：最大最大迭代次数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 最大迭代次数。 |

### setNumberOfObjects(int value) {#setNumberOfObjects-int-}
```
public final void setNumberOfObjects(int value)
```


设置要将初始图像分离为的对象数量（可选），默认值为 2（对象和背景）。

值：对象的数量。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 将初始图像分割为的对象数量（可选），默认值为 2（对象和背景）。 |

### setObjectsPoints(Point[][] value) {#setObjectsPoints-com.aspose.psd.Point-----}
```
public final void setObjectsPoints(Point[][] value)
```


设置属于分离对象的点（可选）NumberOfObjects 坐标，这些坐标属于初始图像的 NumberOfObjects 个对象。此参数用于提高分割方法的精度。

值：对象的点。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | 属于分离对象的点（可选）NumberOfObjects 坐标，这些坐标属于初始图像的 NumberOfObjects 个对象。 |

### setObjectsRectangles(Rectangle[] value) {#setObjectsRectangles-com.aspose.psd.Rectangle---}
```
public final void setObjectsRectangles(Rectangle[] value)
```


设置属于分离对象的对象矩形（可选）。此参数用于提高分割方法的精度。

值：对象的矩形。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | 属于分离对象的对象矩形（可选）。 |

### setOrphanedPoints(Point[] value) {#setOrphanedPoints-com.aspose.psd.Point---}
```
public final void setOrphanedPoints(Point[] value)
```


设置不再属于任何对象的点（可选）。此参数仅在重新分割的情况下使用。

值：孤立的点。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | 不再属于任何对象的点（可选）。 |

### setPrecision(double value) {#setPrecision-double-}
```
public final void setPrecision(double value)
```


设置分割方法的精度（可选）。

值：分割方法的精度（可选）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double | 分割方法的精度（可选）。 |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

