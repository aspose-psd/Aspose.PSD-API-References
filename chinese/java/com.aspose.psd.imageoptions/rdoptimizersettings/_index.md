---
title: "RdOptimizerSettings"
second_title: "Aspose.PSD 的 Java API 参考"
description: "RD 优化器设置类"
type: docs
weight: 22
url: /zh/java/com.aspose.psd.imageoptions/rdoptimizersettings/
---

**Inheritance:**
java.lang.Object
```
public class RdOptimizerSettings
```

RD 优化器设置类
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RdOptimizerSettings()](#RdOptimizerSettings--) | 初始化 RdOptimizerSettings 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [create()](#create--) | 创建此实例。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBppMax()](#getBppMax--) | 获取以每像素位数为考虑的最大 R 值。 |
| [getBppScale()](#getBppScale--) | 获取 BPP（每像素位数）缩放因子。 |
| [getClass()](#getClass--) |  |
| [getDcClamp_internalized()](#getDcClamp-internalized--) | 获取 DC 限幅值，以限制块中左上角第一个像素的量化值范围。 |
| [getDiscretizedBppMax()](#getDiscretizedBppMax--) | 获取用于考虑的最大 R 值。 |
| [getMaxChannel_internalized()](#getMaxChannel-internalized--) | 获取要使用的最大颜色通道数。 |
| [getMaxPixelValue()](#getMaxPixelValue--) | 获取最大像素值。 |
| [getMaxQ()](#getMaxQ--) | 获取最大量化值。 |
| [getMinQ()](#getMinQ--) | 获取允许的最小量化值。 |
| [getPsnrMax()](#getPsnrMax--) | 获取 PSNR 的最大预期值。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBppMax(double value)](#setBppMax-double-) | 设置用于考虑的最大 R 值（以每像素位数计）。 |
| [setBppScale(int value)](#setBppScale-int-) | 设置 BPP（每像素位数）缩放因子。 |
| [setMaxChannel_internalized(int value)](#setMaxChannel-internalized-int-) | 设置要使用的最大颜色通道数。 |
| [setMaxQ(int value)](#setMaxQ-int-) | 设置最大量化值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RdOptimizerSettings() {#RdOptimizerSettings--}
```
public RdOptimizerSettings()
```


初始化 RdOptimizerSettings 类的新实例。

### create() {#create--}
```
public static RdOptimizerSettings create()
```


创建此实例。

**Returns:**
[RdOptimizerSettings](../../com.aspose.psd.imageoptions/rdoptimizersettings) - returns RDOptimizerSettings class instance
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
### getBppMax() {#getBppMax--}
```
public double getBppMax()
```


获取以每像素位数为考虑的最大 R 值。

**Returns:**
double - 用于考虑的最大 R 值（以每像素位数计）。
### getBppScale() {#getBppScale--}
```
public int getBppScale()
```


获取 BPP（每像素位数）缩放因子。

**Returns:**
int - BPP 缩放因子。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDcClamp_internalized() {#getDcClamp-internalized--}
```
public int getDcClamp_internalized()
```


获取 DC 限幅值，以限制块中左上角第一个像素的量化值范围。

**Returns:**
int - DC 限幅值。
### getDiscretizedBppMax() {#getDiscretizedBppMax--}
```
public int getDiscretizedBppMax()
```


获取用于考虑的最大 R 值。

**Returns:**
int - 用于考虑的最大 R 值。
### getMaxChannel_internalized() {#getMaxChannel-internalized--}
```
public int getMaxChannel_internalized()
```


获取要使用的最大颜色通道数。

**Returns:**
int - 最大颜色通道索引。
### getMaxPixelValue() {#getMaxPixelValue--}
```
public int getMaxPixelValue()
```


获取最大像素值。

**Returns:**
int - 最大的最大像素值。
### getMaxQ() {#getMaxQ--}
```
public int getMaxQ()
```


获取最大量化值。

**Returns:**
int - 最大量化值。
### getMinQ() {#getMinQ--}
```
public int getMinQ()
```


获取允许的最小量化值。

**Returns:**
int - 最小的允许的最小量化值。
### getPsnrMax() {#getPsnrMax--}
```
public int getPsnrMax()
```


获取 PSNR 的最大预期值。

**Returns:**
int - 最大的最大像素值。
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




### setBppMax(double value) {#setBppMax-double-}
```
public void setBppMax(double value)
```


设置用于考虑的最大 R 值（以每像素位数计）。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double | 用于考虑的最大 R 值（以每像素位数计）。 |

### setBppScale(int value) {#setBppScale-int-}
```
public void setBppScale(int value)
```


设置 BPP（每像素位数）缩放因子。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | BPP 缩放因子。 |

### setMaxChannel_internalized(int value) {#setMaxChannel-internalized-int-}
```
public void setMaxChannel_internalized(int value)
```


设置要使用的最大颜色通道数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 最大颜色通道索引。 |

### setMaxQ(int value) {#setMaxQ-int-}
```
public void setMaxQ(int value)
```


设置最大量化值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 最大量化值。 |

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

