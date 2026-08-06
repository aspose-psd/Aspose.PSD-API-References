---
title: "ColorantCmyk"
second_title: "Aspose.PSD 的 Java API 参考"
description: "表示 CMYK 色料。"
type: docs
weight: 13
url: /zh/java/com.aspose.psd.xmp.types.complex.colorant/colorantcmyk/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase), [com.aspose.psd.xmp.types.complex.colorant.ColorantBase](../../com.aspose.psd.xmp.types.complex.colorant/colorantbase)
```
public final class ColorantCmyk extends ColorantBase
```

表示 CMYK 色料。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ColorantCmyk()](#ColorantCmyk--) | 初始化 ColorantCmyk 类的新实例。 |
| [ColorantCmyk(float black, float cyan, float magenta, float yellow)](#ColorantCmyk-float-float-float-float-) | 初始化 ColorantCmyk 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [ColorValueMax](#ColorValueMax) | CMYK 颜色剂中的颜色最大值。 |
| [ColorValueMin](#ColorValueMin) | CMYK 颜色剂中的颜色最小值。 |
## Methods

| Method | 描述 |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | 添加指定的键。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlack()](#getBlack--) | 获取或设置黑色组件的值。 |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | 获取或设置颜色的类型。 |
| [getCyan()](#getCyan--) | 获取或设置青色组件的值。 |
| [getMagenta()](#getMagenta--) | 获取或设置品红组件的值。 |
| [getMode()](#getMode--) | 获取 ColorMode。 |
| [getNamespaceUri()](#getNamespaceUri--) | 获取默认命名空间 URI。 |
| [getPrefix()](#getPrefix--) | 获取前缀。 |
| [getSwatchName()](#getSwatchName--) | 获取或设置色板的名称。 |
| [getXmpRepresentation()](#getXmpRepresentation--) | 获取 XMP 格式的字符串值。 |
| [getYellow()](#getYellow--) | 获取或设置黄色组件的值。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlack(float value)](#setBlack-float-) | 获取或设置黑色组件的值。 |
| [setColorType(int value)](#setColorType-int-) | 获取或设置颜色的类型。 |
| [setCyan(float value)](#setCyan-float-) | 获取或设置青色组件的值。 |
| [setMagenta(float value)](#setMagenta-float-) | 获取或设置品红组件的值。 |
| [setSwatchName(String value)](#setSwatchName-java.lang.String-) | 获取或设置色板的名称。 |
| [setYellow(float value)](#setYellow-float-) | 获取或设置黄色组件的值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorantCmyk() {#ColorantCmyk--}
```
public ColorantCmyk()
```


初始化 ColorantCmyk 类的新实例。

### ColorantCmyk(float black, float cyan, float magenta, float yellow) {#ColorantCmyk-float-float-float-float-}
```
public ColorantCmyk(float black, float cyan, float magenta, float yellow)
```


初始化 ColorantCmyk 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 黑色 | float | 黑色组件的值。 |
| 青色 | float | 青色组件的值。 |
| 品红 | float | 品红组件的值。 |
| 黄色 | float | 黄色组件的值。 |

### ColorValueMax {#ColorValueMax}
```
public static final float ColorValueMax
```


CMYK 颜色剂中的颜色最大值。

### ColorValueMin {#ColorValueMin}
```
public static final float ColorValueMin
```


CMYK 颜色剂中的颜色最小值。

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
### getBlack() {#getBlack--}
```
public float getBlack()
```


获取或设置黑色组件的值。

值：黑色组件的值。

**Returns:**
float
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
### getCyan() {#getCyan--}
```
public float getCyan()
```


获取或设置青色组件的值。

值：青色分量值。

**Returns:**
float
### getMagenta() {#getMagenta--}
```
public float getMagenta()
```


获取或设置品红组件的值。

值：品红色分量值。

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
### getYellow() {#getYellow--}
```
public float getYellow()
```


获取或设置黄色组件的值。

值：黄色分量值。

**Returns:**
float
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




### setBlack(float value) {#setBlack-float-}
```
public void setBlack(float value)
```


获取或设置黑色组件的值。

值：黑色组件的值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float |  |

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

### setCyan(float value) {#setCyan-float-}
```
public void setCyan(float value)
```


获取或设置青色组件的值。

值：青色分量值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float |  |

### setMagenta(float value) {#setMagenta-float-}
```
public void setMagenta(float value)
```


获取或设置品红组件的值。

值：品红色分量值。

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

### setYellow(float value) {#setYellow-float-}
```
public void setYellow(float value)
```


获取或设置黄色组件的值。

值：黄色分量值。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | float |  |

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

