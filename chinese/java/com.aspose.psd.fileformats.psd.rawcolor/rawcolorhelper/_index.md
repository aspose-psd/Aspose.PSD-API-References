---
title: "RawColorHelper"
second_title: "Aspose.PSD 的 Java API 参考"
description: "Raw Color Helper 类帮助使用预定义的通道元数据更快地创建 RawColor。"
type: docs
weight: 12
url: /zh/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolorhelper/
---

**Inheritance:**
java.lang.Object
```
public class RawColorHelper
```

Raw Color Helper Class 有助于使用预定义的通道元数据更快速地创建 RawColor。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RawColorHelper()](#RawColorHelper--) |  |
## Methods

| Method | 描述 |
| --- | --- |
| [createArgb16BitColor(int a, int r, int g, int b)](#createArgb16BitColor-int-int-int-int-) | 创建每通道 16 位的 ARGB 颜色。 |
| [createArgb8BitColor(byte a, byte r, byte g, byte b)](#createArgb8BitColor-byte-byte-byte-byte-) | 创建每通道 8 位的 ARGB 颜色。 |
| [createArgb8BitColor(Color drawingColor)](#createArgb8BitColor-com.aspose.psd.Color-) | 从 Drawing.Color 创建每通道 8 位的 ARGB 颜色。 |
| [createCmyk16BitBitColor(int c, int m, int y, int k)](#createCmyk16BitBitColor-int-int-int-int-) | 创建每通道 16 位的 CMYK 颜色。 |
| [createCmyk8BitColor(byte c, byte m, byte y, byte k)](#createCmyk8BitColor-byte-byte-byte-byte-) | 创建每通道 8 位的 CMYK 颜色。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RawColorHelper() {#RawColorHelper--}
```
public RawColorHelper()
```


### createArgb16BitColor(int a, int r, int g, int b) {#createArgb16BitColor-int-int-int-int-}
```
public static RawColor createArgb16BitColor(int a, int r, int g, int b)
```


创建每通道 16 位的 ARGB 颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| a | int | Alpha 组件值 (0-65535)。 |
| r | int | 红色组件值 (0-65535)。 |
| g | int | 绿色组件值 (0-65535)。 |
|  | b | int | 蓝色组件值 (0-65535)。 |

--------------------

颜色组件按以下顺序打包到 64 位整数中：alpha（第 48-63 位），red（第 32-47 位），green（第 16-31 位），以及 blue（第 0-15 位）。 |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(byte a, byte r, byte g, byte b) {#createArgb8BitColor-byte-byte-byte-byte-}
```
public static RawColor createArgb8BitColor(byte a, byte r, byte g, byte b)
```


创建每通道 8 位的 ARGB 颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| a | byte | Alpha 组件值 (0-255)。 |
| r | byte | 红色组件值 (0-255)。 |
| g | byte | 绿色分量值 (0-255)。 |
|  | b | byte | 蓝色分量值 (0-255)。 |

--------------------

颜色分量按以下顺序打包到 32 位整数中：alpha（第 24-31 位），red（第 16-23 位），green（第 8-15 位），以及 blue（第 0-7 位）。 |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createArgb8BitColor(Color drawingColor) {#createArgb8BitColor-com.aspose.psd.Color-}
```
public static RawColor createArgb8BitColor(Color drawingColor)
```


从 Drawing.Color 创建每通道 8 位的 ARGB 颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
|  | drawingColor | [Color](../../com.aspose.psd/color) | System.Drawing Color |

--------------------

颜色分量按以下顺序打包到 32 位整数中：alpha（第 24-31 位），red（第 16-23 位），green（第 8-15 位），以及 blue（第 0-7 位）。 |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the ARGB color.
### createCmyk16BitBitColor(int c, int m, int y, int k) {#createCmyk16BitBitColor-int-int-int-int-}
```
public static RawColor createCmyk16BitBitColor(int c, int m, int y, int k)
```


创建每通道 16 位的 CMYK 颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| c | int | 青色分量值 (0-65535)。 |
| m | int | 品红分量值 (0-65535)。 |
| y | int | 黄色分量值 (0-65535)。 |
|  | k | int | 键（黑）分量值 (0-65535)。 |

--------------------

颜色分量按以下顺序打包到 64 位整数中：cyan（第 48-63 位），magenta（第 32-47 位），yellow（第 16-31 位），以及 key/black（第 0-15 位）。 |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
### createCmyk8BitColor(byte c, byte m, byte y, byte k) {#createCmyk8BitColor-byte-byte-byte-byte-}
```
public static RawColor createCmyk8BitColor(byte c, byte m, byte y, byte k)
```


创建每通道 8 位的 CMYK 颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| c | byte | 青色分量值 (0-255)。 |
| m | byte | 品红分量值 (0-255)。 |
| y | byte | 黄色分量值 (0-255)。 |
|  | k | byte | 键（黑）分量值 (0-255)。 |

--------------------

颜色分量按以下顺序打包到 32 位整数中：cyan（第 24-31 位），magenta（第 16-23 位），yellow（第 8-15 位），以及 key/black（第 0-7 位）。 |

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) - A new [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) instance representing the CMYK color.
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

