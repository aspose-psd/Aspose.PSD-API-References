---
title: "GradientHelper"
second_title: "Aspose.PSD 的 Java API 参考"
description: "实现梯度属性数据转换的辅助类。"
type: docs
weight: 34
url: /zh/java/com.aspose.psd.fileformats.psd.layers.layerresources/gradienthelper/
---

**Inheritance:**
java.lang.Object
```
public final class GradientHelper
```

实现梯度属性数据转换的辅助类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [GradientHelper()](#GradientHelper--) |  |
## 字段

| 字段 | 描述 |
| --- | --- |
| [IntModelHSB](#IntModelHSB) | HSBL 颜色模型整数常量，用于噪声渐变。 |
| [IntModelLAB](#IntModelLAB) | LBCL 颜色模型的整数常量，用于噪声渐变。 |
| [IntModelRGB](#IntModelRGB) | RGBC 颜色模型的整数常量，用于噪声渐变。 |
| [StrGradientNoise](#StrGradientNoise) | 噪声渐变字符串常量。 |
| [StrGradientSolid](#StrGradientSolid) | 实色渐变字符串常量。 |
| [StrModelHSB](#StrModelHSB) | 用于噪声渐变的 HSBL 颜色模型字符串常量。 |
| [StrModelLAB](#StrModelLAB) | 用于噪声渐变的 LBCL 颜色模型字符串常量。 |
| [StrModelRGB](#StrModelRGB) | 用于噪声渐变的 RGBC 颜色模型字符串常量。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [gradientKindToStr(int gradientKind)](#gradientKindToStr-int-) | 将 GradientKind 值转换为字符串。 |
| [hashCode()](#hashCode--) |  |
| [intToNoiseColorModel(short colorModel)](#intToNoiseColorModel-short-) | 将噪声颜色模型的整数值转换为 NoiseColorModel。 |
| [noiseColorModelToInt(short colorModel)](#noiseColorModelToInt-short-) | 将 NoiseColorModel 实例转换为噪声颜色模型的整数值。 |
| [noiseColorModelToStr(short colorModel)](#noiseColorModelToStr-short-) | 将 NoiseColorModel 值转换为字符串。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [strToGradientKind(String str)](#strToGradientKind-java.lang.String-) | 将字符串值转换为 GradientKind。 |
| [strToNoiseColorModel(String colorModel)](#strToNoiseColorModel-java.lang.String-) | 将字符串值转换为 NoiseColorModel。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientHelper() {#GradientHelper--}
```
public GradientHelper()
```


### IntModelHSB {#IntModelHSB}
```
public static final short IntModelHSB
```


HSBL 颜色模型整数常量，用于噪声渐变。

### IntModelLAB {#IntModelLAB}
```
public static final short IntModelLAB
```


LBCL 颜色模型的整数常量，用于噪声渐变。

### IntModelRGB {#IntModelRGB}
```
public static final short IntModelRGB
```


RGBC 颜色模型的整数常量，用于噪声渐变。

### StrGradientNoise {#StrGradientNoise}
```
public static final String StrGradientNoise
```


噪声渐变字符串常量。

### StrGradientSolid {#StrGradientSolid}
```
public static final String StrGradientSolid
```


实色渐变字符串常量。

### StrModelHSB {#StrModelHSB}
```
public static final String StrModelHSB
```


用于噪声渐变的 HSBL 颜色模型字符串常量。

### StrModelLAB {#StrModelLAB}
```
public static final String StrModelLAB
```


用于噪声渐变的 LBCL 颜色模型字符串常量。

### StrModelRGB {#StrModelRGB}
```
public static final String StrModelRGB
```


用于噪声渐变的 RGBC 颜色模型字符串常量。

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
### gradientKindToStr(int gradientKind) {#gradientKindToStr-int-}
```
public static String gradientKindToStr(int gradientKind)
```


将 GradientKind 值转换为字符串。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| gradientKind | int | GradientKind 值。 |

**Returns:**
java.lang.String - 字符串值。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### intToNoiseColorModel(short colorModel) {#intToNoiseColorModel-short-}
```
public static short intToNoiseColorModel(short colorModel)
```


将噪声颜色模型的整数值转换为 NoiseColorModel。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| colorModel | short | 噪声颜色模型的整数值。 |

**Returns:**
short - NoiseColorModel 实例。
### noiseColorModelToInt(short colorModel) {#noiseColorModelToInt-short-}
```
public static short noiseColorModelToInt(short colorModel)
```


将 NoiseColorModel 实例转换为噪声颜色模型的整数值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| colorModel | short | NoiseColorModel 实例。 |

**Returns:**
short - 噪声渐变颜色模型的整数值。
### noiseColorModelToStr(short colorModel) {#noiseColorModelToStr-short-}
```
public static String noiseColorModelToStr(short colorModel)
```


将 NoiseColorModel 值转换为字符串。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| colorModel | short | NoiseColorModel 值。 |

**Returns:**
java.lang.String - 颜色模型的字符串值。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### strToGradientKind(String str) {#strToGradientKind-java.lang.String-}
```
public static int strToGradientKind(String str)
```


将字符串值转换为 GradientKind。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| str | java.lang.String | 字符串值。 |

**Returns:**
int - GradientKind 值。
### strToNoiseColorModel(String colorModel) {#strToNoiseColorModel-java.lang.String-}
```
public static short strToNoiseColorModel(String colorModel)
```


将字符串值转换为 NoiseColorModel。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| colorModel | java.lang.String | 字符串值。 |

**Returns:**
short - NoiseColorModel 值。
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

