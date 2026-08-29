---
title: "颜色调色板"
second_title: "Aspose.PSD 的 Java API 参考"
description: "定义组成颜色调色板的颜色数组。"
type: docs
weight: 27
url: /zh/java/com.aspose.psd/colorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public final class ColorPalette implements IColorPalette
```

定义组成颜色调色板的颜色数组。颜色为 32 位 ARGB 颜色。不可继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ColorPalette(int[] argb32Entries, boolean isCompactPalette)](#ColorPalette-int---boolean-) | 初始化 ColorPalette 类的新实例。 |
| [ColorPalette(int[] argb32Entries)](#ColorPalette-int---) | 初始化 ColorPalette 类的新实例，并且 IsCompactPalette 为 false。 |
| [ColorPalette(Color[] entries, boolean isCompactPalette)](#ColorPalette-com.aspose.psd.Color---boolean-) | 初始化 ColorPalette 类的新实例。 |
| [ColorPalette(Color[] entries)](#ColorPalette-com.aspose.psd.Color---) | 初始化 ColorPalette 类的新实例，并且 IsCompactPalette 为 false。 |
## Methods

| Method | 描述 |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | 复制调色板。 |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | 复制调色板。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | 根据索引获取 32 位 ARGB 调色板颜色。 |
| [getArgb32Entries()](#getArgb32Entries--) | 获取 32 位 ARGB 结构的数组。 |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | 根据索引获取调色板颜色。 |
| [getEntries()](#getEntries--) | 获取 com.aspose.psd.Color 结构的数组。 |
| [getEntriesCount()](#getEntriesCount--) | 获取条目计数。 |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | 获取最近颜色的索引。 |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | 获取最近颜色的索引。 |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | 获取或设置指示是否使用紧凑调色板的值。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorPalette(int[] argb32Entries, boolean isCompactPalette) {#ColorPalette-int---boolean-}
```
public ColorPalette(int[] argb32Entries, boolean isCompactPalette)
```


初始化 ColorPalette 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| argb32Entries | int[] | 32 位 ARGB 颜色调色板条目。 |
| isCompactPalette | boolean | 指示调色板是否紧凑。 |

### ColorPalette(int[] argb32Entries) {#ColorPalette-int---}
```
public ColorPalette(int[] argb32Entries)
```


初始化 ColorPalette 类的新实例，并且 IsCompactPalette 为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| argb32Entries | int[] | 32 位 ARGB 颜色调色板条目。 |

### ColorPalette(Color[] entries, boolean isCompactPalette) {#ColorPalette-com.aspose.psd.Color---boolean-}
```
public ColorPalette(Color[] entries, boolean isCompactPalette)
```


初始化 ColorPalette 类的新实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | 颜色调色板条目。 |
| isCompactPalette | boolean | 指示调色板是否紧凑。 |

### ColorPalette(Color[] entries) {#ColorPalette-com.aspose.psd.Color---}
```
public ColorPalette(Color[] entries)
```


初始化 ColorPalette 类的新实例，并且 IsCompactPalette 为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | 颜色调色板条目。 |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette)
```


复制调色板。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 颜色调色板。 |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


复制调色板。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 颜色调色板。 |
| useCompactPalette | boolean | 指示调色板是否紧凑。 |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
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
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public int getArgb32Color(int index)
```


根据索引获取 32 位 ARGB 调色板颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| index | int | 32 位 ARGB 调色板颜色索引。 |

**Returns:**
int - 由索引指定的颜色调色板条目。
### getArgb32Entries() {#getArgb32Entries--}
```
public int[] getArgb32Entries()
```


获取 32 位 ARGB 结构的数组。

**Returns:**
int[] - 条目。组成此 Aspose.Imaging.ColorPalette 的 32 位 ARGB 结构数组。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor(int index) {#getColor-int-}
```
public Color getColor(int index)
```


根据索引获取调色板颜色。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| index | int | 调色板颜色索引。 |

**Returns:**
[Color](../../com.aspose.psd/color) - The color palette entry specified by the  index .
### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


获取 com.aspose.psd.Color 结构的数组。

**Returns:**
com.aspose.psd.Color[] - 条目。组成此 Aspose.Imaging.ColorPalette 的 com.aspose.psd.Color 结构数组。
### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


获取条目计数。

**Returns:**
int - 条目计数。
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public int getNearestColorIndex(Color color)
```


获取最近颜色的索引。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | 颜色。 |

**Returns:**
int - 最近颜色的索引。
### getNearestColorIndex(int argb32Color) {#getNearestColorIndex-int-}
```
public int getNearestColorIndex(int argb32Color)
```


获取最近颜色的索引。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| argb32Color | int | 32 位 ARGB 颜色。 |

**Returns:**
int - 最近颜色的索引。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


获取或设置指示是否使用紧凑调色板的值。

**Returns:**
布尔型 - 如果使用紧凑调色板则为 true；否则为 false。

紧凑调色板意味着图像将在可能的情况下仅包含指定的调色板条目，换句话说，图像将更紧凑并占用更少的空间；否则将有 2^BitsPerPixel 条目，图像将为所有可能的调色板条目预留更多空间。将此值设为 true 并更改调色板条目可能会导致性能惩罚，因为可能会发生数据移动，请谨慎使用。
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

