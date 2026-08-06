---
title: "RawColor"
second_title: "Aspose.PSD 的 Java API 参考"
description: "Raw Color Class 有助于存储任意通道数、任意颜色模式和任意位深度的颜色。请注意，一些内部类在将 RawColor 转换为其原生格式时可能会出现问题，因此如果 API 为您提供 CMYK 颜色，使用提供的格式更可靠。"
type: docs
weight: 11
url: /zh/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolor/
---

**Inheritance:**
java.lang.Object
```
public final class RawColor
```

Raw Color Class 有助于存储任意通道数、任意颜色模式和任意位深度的颜色。请注意，一些内部类在将 RawColor 转换为其原生格式时可能会出现问题，因此如果 API 为您提供 CMYK 颜色，使用提供的格式更可靠。另外，可能会出现某些情况下 Raw Color 可以被转换的情况。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RawColor(ColorComponent[] components)](#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---) | 初始化 [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) 类的新实例。 |
| [RawColor(PixelDataFormat pixelDataFormat)](#RawColor-com.aspose.psd.PixelDataFormat-) |  |
| [RawColor(PixelDataFormat pixelDataFormat, short colorMode)](#RawColor-com.aspose.psd.PixelDataFormat-short-) | 使用预定义的颜色模式，从像素数据格式初始化 [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) 类的新实例。 |
## Methods

| Method | 描述 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 Object 是否等于此实例。 |
| [getAsInt()](#getAsInt--) | 在可能的情况下，以 int 形式获取颜色。 |
| [getAsLong()](#getAsLong--) | 在可能的情况下，以 long 形式获取颜色。 |
| [getBitDepth()](#getBitDepth--) | 获取 Raw Color 的位深度。 |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | 颜色应遵循的模式。 |
| [getColorModeName()](#getColorModeName--) | 获取颜色模式的名称。 |
| [getComponents()](#getComponents--) | 获取颜色的分量。 |
| [hashCode()](#hashCode--) | 获取当前对象的哈希码。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(RawColor left, RawColor right)](#op-Equality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | 实现运算符 ==。 |
| [op_Inequality(RawColor left, RawColor right)](#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | 实现运算符 !=。 |
| [setAsInt(int value)](#setAsInt-int-) | 如果可能，将数据从 int 参数设置到所有通道。 |
| [setAsLong(long value)](#setAsLong-long-) | 如果可能，将数据从 int 参数设置到所有通道。 |
| [setColorMode(short value)](#setColorMode-short-) | 颜色应遵循的模式。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RawColor(ColorComponent[] components) {#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---}
```
public RawColor(ColorComponent[] components)
```


初始化 [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| components | [ColorComponent\[\]](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) | 自定义颜色组件。 |

### RawColor(PixelDataFormat pixelDataFormat) {#RawColor-com.aspose.psd.PixelDataFormat-}
```
public RawColor(PixelDataFormat pixelDataFormat)
```


**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) |  |

### RawColor(PixelDataFormat pixelDataFormat, short colorMode) {#RawColor-com.aspose.psd.PixelDataFormat-short-}
```
public RawColor(PixelDataFormat pixelDataFormat, short colorMode)
```


使用预定义的颜色模式，从像素数据格式初始化 [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | 像素数据格式。 |
| colorMode | short |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的 Object 是否等于此实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的对象。 |

**Returns:**
布尔值 -  true  如果指定的对象等于此实例；否则为  false .
### getAsInt() {#getAsInt--}
```
public final int getAsInt()
```


在可能的情况下，以 int 形式获取颜色。

**Returns:**
int - 通道数据存储在 Int 中
### getAsLong() {#getAsLong--}
```
public final long getAsLong()
```


在可能的情况下，以 long 形式获取颜色。

**Returns:**
long - 通道数据存储在 Int 中
### getBitDepth() {#getBitDepth--}
```
public final int getBitDepth()
```


获取原始颜色的位深度。例如，对于每通道/组件为 8 位的 ARGB 颜色，完整 ARGB 颜色的位深度为 32 位；每通道/组件为 16 位时，位深度为 64 位。位深度是所有通道位深度之和。如果不同通道具有不同的位深度，也可以。

**Returns:**
int - 所有通道位深度之和
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


颜色应遵循的模式。

**Returns:**
short
### getColorModeName() {#getColorModeName--}
```
public final String getColorModeName()
```


获取颜色模式的名称。颜色模式名称由通道/组件名称累积而成。

**Returns:**
java.lang.String - 包含颜色模式名称的字符串
### getComponents() {#getComponents--}
```
public final ColorComponent[] getComponents()
```


获取颜色的组件。每个组件是单独的通道，如果使用不常见的配色方案，最好分别处理每个通道。

值：颜色的组件

**Returns:**
com.aspose.psd.fileformats.psd.rawcolor.ColorComponent[]
### hashCode() {#hashCode--}
```
public int hashCode()
```


获取当前对象的哈希码。

**Returns:**
int - 哈希码。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(RawColor left, RawColor right) {#op-Equality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public static boolean op_Equality(RawColor left, RawColor right)
```


实现运算符 ==。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | 第一个 RawColor。 |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | 第二个 RawColor。 |

**Returns:**
boolean - 运算符的结果。
### op_Inequality(RawColor left, RawColor right) {#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public static boolean op_Inequality(RawColor left, RawColor right)
```


实现运算符 !=。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | 第一个 RawColor。 |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | 第二个 RawColor。 |

**Returns:**
boolean - 运算符的结果。
### setAsInt(int value) {#setAsInt-int-}
```
public final void setAsInt(int value)
```


如果可能，将数据从 int 参数设置到所有通道。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | int | 包含组件数据的 int 值 |

### setAsLong(long value) {#setAsLong-long-}
```
public final void setAsLong(long value)
```


如果可能，将数据从 int 参数设置到所有通道。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | long | 包含组件数据的 int 值 |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


颜色应遵循的模式。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| 值 | short |  |

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

