---
title: "ColorantLab"
second_title: "Aspose.PSD 的 Java API 参考"
description: "表示 LAB 色料。"
type: docs
weight: 14
url: /zh/java/com.aspose.psd.xmp.types.complex.colorant/colorantlab/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase), [com.aspose.psd.xmp.types.complex.colorant.ColorantBase](../../com.aspose.psd.xmp.types.complex.colorant/colorantbase)
```
public final class ColorantLab extends ColorantBase
```

表示 LAB 色料。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ColorantLab()](#ColorantLab--) | 初始化 ColorantLab 类的新实例。 |
| [ColorantLab(int a, int b, float l)](#ColorantLab-int-int-float-) | 初始化 ColorantLab 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [MaxA](#MaxA) | 最大 A 分量值 |
| [MaxB](#MaxB) | 最大 A 分量值 |
| [MaxL](#MaxL) | 最大 A 分量值 |
| [MinA](#MinA) | 最小 A 分量值 |
| [MinB](#MinB) | 最小 B 分量值 |
| [MinL](#MinL) | 最小 L 分量值 |
## Methods

| Method | 描述 |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | 添加指定的键。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getA()](#getA--) | 获取或设置 A 分量。 |
| [getB()](#getB--) | 获取或设置 B 分量。 |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | 获取或设置颜色的类型。 |
| [getL()](#getL--) | 获取或设置 L 分量。 |
| [getMode()](#getMode--) | 获取 ColorMode。 |
| [getNamespaceUri()](#getNamespaceUri--) | 获取默认命名空间 URI。 |
| [getPrefix()](#getPrefix--) | 获取前缀。 |
| [getSwatchName()](#getSwatchName--) | 获取或设置色板的名称。 |
| [getXmpRepresentation()](#getXmpRepresentation--) | 获取 XMP 格式的字符串值。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setA(int value)](#setA-int-) | 获取或设置 A 分量。 |
| [setB(int value)](#setB-int-) | 获取或设置 B 分量。 |
| [setColorType(int value)](#setColorType-int-) | 获取或设置颜色的类型。 |
| [setL(float value)](#setL-float-) | 获取或设置 L 分量。 |
| [setSwatchName(String value)](#setSwatchName-java.lang.String-) | 获取或设置色板的名称。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorantLab() {#ColorantLab--}
```
public ColorantLab()
```


初始化 ColorantLab 类的新实例。

### ColorantLab(int a, int b, float l) {#ColorantLab-int-int-float-}
```
public ColorantLab(int a, int b, float l)
```


初始化 ColorantLab 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| a | int | A 分量。 |
| b | int | B 分量。 |
| l | float | L 组件。 |

### MaxA {#MaxA}
```
public static final int MaxA
```


最大 A 分量值

### MaxB {#MaxB}
```
public static final int MaxB
```


最大 A 分量值

### MaxL {#MaxL}
```
public static final float MaxL
```


最大 A 分量值

### MinA {#MinA}
```
public static final int MinA
```


最小 A 分量值

### MinB {#MinB}
```
public static final int MinB
```


最小 B 分量值

### MinL {#MinL}
```
public static final float MinL
```


最小 L 分量值

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


添加指定的键。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| key | java.lang.String | key 的字符串表示形式，用于标识已添加的值。 |
| 值 | java.lang.Object | 要添加到的值。 |

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
### getA() {#getA--}
```
public int getA()
```


获取或设置 A 分量。

值：该 A 组件。

**Returns:**
int
### getB() {#getB--}
```
public int getB()
```


获取或设置 B 分量。

值：该 B 组件。

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorType() {#getColorType--}
```
public int getColorType()
```


获取或设置颜色的类型。

值：该颜色的类型。

**Returns:**
int
### getL() {#getL--}
```
public float getL()
```


获取或设置 L 分量。

值：该 L 组件。

**Returns:**
float
### getMode() {#getMode--}
```
public int getMode()
```


获取 ColorMode。

值：该颜色模式。

**Returns:**
int
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


获取默认命名空间 URI。

**Returns:**
java.lang.String - 默认的命名空间 URI。
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


获取前缀。

**Returns:**
java.lang.String - 前缀。
### getSwatchName() {#getSwatchName--}
```
public String getSwatchName()
```


获取或设置色板的名称。

值：该色板的名称。

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


获取 XMP 格式的字符串值。

**Returns:**
java.lang.String - 返回 XMP 格式的字符串值。
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




### setA(int value) {#setA-int-}
```
public void setA(int value)
```


获取或设置 A 分量。

值：该 A 组件。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setB(int value) {#setB-int-}
```
public void setB(int value)
```


获取或设置 B 分量。

值：该 B 组件。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


获取或设置颜色的类型。

值：该颜色的类型。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int |  |

### setL(float value) {#setL-float-}
```
public void setL(float value)
```


获取或设置 L 分量。

值：该 L 组件。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setSwatchName(String value) {#setSwatchName-java.lang.String-}
```
public void setSwatchName(String value)
```


获取或设置色板的名称。

值：该色板的名称。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

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

