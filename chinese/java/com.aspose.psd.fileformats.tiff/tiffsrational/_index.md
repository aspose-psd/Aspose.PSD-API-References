---
title: "TiffSRational"
second_title: "Aspose.PSD 的 Java API 参考"
description: "tiff 有理数类型。"
type: docs
weight: 13
url: /zh/java/com.aspose.psd.fileformats.tiff/tiffsrational/
---

**Inheritance:**
java.lang.Object
```
public class TiffSRational
```

tiff 有理数类型。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TiffSRational()](#TiffSRational--) | 初始化 TiffSRational 类的新实例。 |
| [TiffSRational(int value)](#TiffSRational-int-) | 初始化 TiffRational 类的新实例。 |
| [TiffSRational(int nominator, int denominator)](#TiffSRational-int-int-) | 初始化 TiffSRational 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [Epsilon](#Epsilon) | 用于分数计算的 epsilon |
## Methods

| Method | 描述 |
| --- | --- |
| [approximateFraction(double value)](#approximateFraction-double-) | 将提供的值近似为分数。 |
| [approximateFraction(double value, double epsilon)](#approximateFraction-double-double-) | 将提供的值近似为分数。 |
| [approximateFraction(float value)](#approximateFraction-float-) | 将提供的值近似为分数。 |
| [approximateFraction(float value, double epsilon)](#approximateFraction-float-double-) | 将提供的值近似为分数。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 Object 是否等于此实例。 |
| [getClass()](#getClass--) |  |
| [getDenominator()](#getDenominator--) | 获取分母。 |
| [getNominator()](#getNominator--) | 获取分子。 |
| [getValue()](#getValue--) | 获取 float 值。 |
| [getValueD()](#getValueD--) | 获取 double 值。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | 返回 一个  System.String  表示此实例。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffSRational() {#TiffSRational--}
```
public TiffSRational()
```


初始化 TiffSRational 类的新实例。

### TiffSRational(int value) {#TiffSRational-int-}
```
public TiffSRational(int value)
```


初始化 TiffRational 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
|  | 值 | int | 分子值。 |

分子将用作指定的值，且分母将等于 1。 |

### TiffSRational(int nominator, int denominator) {#TiffSRational-int-int-}
```
public TiffSRational(int nominator, int denominator)
```


初始化 TiffSRational 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 分子 | int | 分子。 |
| denominator | int | 该 denominator。 |

### Epsilon {#Epsilon}
```
public static final double Epsilon
```


用于分数计算的 epsilon

### approximateFraction(double value) {#approximateFraction-double-}
```
public static TiffSRational approximateFraction(double value)
```


将提供的值近似为分数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double | 该值。 |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - A rational number having error less than  Epsilon .
### approximateFraction(double value, double epsilon) {#approximateFraction-double-double-}
```
public static TiffSRational approximateFraction(double value, double epsilon)
```


将提供的值近似为分数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | double | 该值。 |
| epsilon | double | 允许的误差。 |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - A rational number having error less than  epsilon .
### approximateFraction(float value) {#approximateFraction-float-}
```
public static TiffSRational approximateFraction(float value)
```


将提供的值近似为分数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float | 该值。 |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - A rational number having error less than  Epsilon .
### approximateFraction(float value, double epsilon) {#approximateFraction-float-double-}
```
public static TiffSRational approximateFraction(float value, double epsilon)
```


将提供的值近似为分数。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float | 该值。 |
| epsilon | double | 允许的误差。 |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - A rational number having error less than  epsilon .
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的 Object 是否等于此实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的 Object。 |

**Returns:**
boolean - 如果指定的 Object 等于此实例，则为 true；否则为 false。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDenominator() {#getDenominator--}
```
public int getDenominator()
```


获取分母。

值：分母。

**Returns:**
int
### getNominator() {#getNominator--}
```
public int getNominator()
```


获取分子。

值：分子。

**Returns:**
int
### getValue() {#getValue--}
```
public float getValue()
```


获取 float 值。

值：float 值。

**Returns:**
float
### getValueD() {#getValueD--}
```
public double getValueD()
```


获取 double 值。

值：双精度值。

**Returns:**
double
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**Returns:**
int - 此实例的哈希码，适用于哈希算法和诸如哈希表之类的数据结构。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```


返回 一个  System.String  表示此实例。

**Returns:**
java.lang.String - 一个  System.String  表示此实例。
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

