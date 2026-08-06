---
title: "PsdColorPalette"
second_title: "Aspose.PSD 的 Java API 参考"
description: "PSD 颜色调色板。"
type: docs
weight: 13
url: /zh/java/com.aspose.psd.fileformats.psd/psdcolorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IPsdColorPalette](../../com.aspose.psd/ipsdcolorpalette)
```
public class PsdColorPalette implements IPsdColorPalette
```

PSD 颜色调色板。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PsdColorPalette(IColorPalette colorPalette)](#PsdColorPalette-com.aspose.psd.IColorPalette-) | 初始化一个新的 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 类实例。 |
| [PsdColorPalette(IColorPalette colorPalette, short transparentIndex)](#PsdColorPalette-com.aspose.psd.IColorPalette-short-) | 初始化一个新的 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 类实例。 |
| [PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)](#PsdColorPalette-byte---boolean-) | 初始化一个新的 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 类实例。 |
| [PsdColorPalette(byte[] rawEntriesData)](#PsdColorPalette-byte---) | 初始化一个新的 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 类实例，并且 IsCompactPalette 为 false。 |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-byte---short-boolean-) | 初始化一个新的 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 类实例。 |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex)](#PsdColorPalette-byte---short-) | 初始化一个新的 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 类实例，并且 IsCompactPalette 为 false。 |
| [PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)](#PsdColorPalette-int---boolean-) | 初始化一个新的 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 类实例。 |
| [PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---boolean-) | 初始化一个新的 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 类实例。 |
| [PsdColorPalette(Color[] colorPaletteEntries)](#PsdColorPalette-com.aspose.psd.Color---) | 初始化一个新的 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 类实例，并且 IsCompactPalette 为 false。 |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---short-boolean-) | 初始化一个新的 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 类实例。 |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)](#PsdColorPalette-com.aspose.psd.Color---short-) | 初始化一个新的 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 类实例，并且 IsCompactPalette 为 false。 |
## Methods

| Method | 描述 |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | 复制调色板。 |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | 复制调色板。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | 根据索引获取 32 位 ARGB 调色板颜色。 |
| [getArgb32Entries()](#getArgb32Entries--) | 获取 32 位 ARGB 颜色的数组。 |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | 根据索引获取调色板颜色。 |
| [getEntries()](#getEntries--) | 获取 [Color](../../com.aspose.psd/color) 结构体的数组。 |
| [getEntriesCount()](#getEntriesCount--) | 获取条目计数。 |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | 获取最近颜色的索引。 |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | 获取最近颜色的索引。 |
| [getRawEntries()](#getRawEntries--) | 获取原始颜色调色板条目数据。 |
| [getRawEntriesCount()](#getRawEntriesCount--) | 获取原始颜色调色板条目计数。 |
| [getTransparentColor()](#getTransparentColor--) | 获取透明颜色。 |
| [getTransparentIndex()](#getTransparentIndex--) | 获取透明颜色的索引。 |
| [hasTransparentColor()](#hasTransparentColor--) | 获取一个值，指示是否存在透明颜色。 |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | 获取一个值，指示调色板是否紧凑。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdColorPalette(IColorPalette colorPalette) {#PsdColorPalette-com.aspose.psd.IColorPalette-}
```
public PsdColorPalette(IColorPalette colorPalette)
```


初始化一个新的 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 类实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 颜色调色板。 |

### PsdColorPalette(IColorPalette colorPalette, short transparentIndex) {#PsdColorPalette-com.aspose.psd.IColorPalette-short-}
```
public PsdColorPalette(IColorPalette colorPalette, short transparentIndex)
```


初始化一个新的 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 类实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 颜色调色板。 |
| transparentIndex | short | 透明颜色索引。 |

### PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette) {#PsdColorPalette-byte---boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)
```


初始化一个新的 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 类实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rawEntriesData | byte[] | 原始条目数据。 |
| isCompactPalette | boolean | 指示调色板是否紧凑。 |

### PsdColorPalette(byte[] rawEntriesData) {#PsdColorPalette-byte---}
```
public PsdColorPalette(byte[] rawEntriesData)
```


初始化一个新的 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 类实例，并且 IsCompactPalette 为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rawEntriesData | byte[] | 原始条目数据。 |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-byte---short-boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)
```


初始化一个新的 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 类实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rawEntriesData | byte[] | 原始条目数据。 |
| transparentIndex | short | 透明颜色索引。注意，该索引不是原始条目索引，而是针对转换后的颜色数组。 |
| useCompactPalette | boolean | 指示调色板是否紧凑。 |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex) {#PsdColorPalette-byte---short-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex)
```


初始化一个新的 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 类实例，并且 IsCompactPalette 为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rawEntriesData | byte[] | 原始条目数据。 |
| transparentIndex | short | 透明颜色索引。注意，该索引不是原始条目索引，而是针对转换后的颜色数组。 |

### PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette) {#PsdColorPalette-int---boolean-}
```
public PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)
```


初始化一个新的 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 类实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| colorPaletteArgb32Entries | int[] | 颜色调色板的 32 位 ARGB 条目。 |
| isCompactPalette | boolean | 指示调色板是否紧凑。 |

### PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)
```


初始化一个新的 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 类实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | 颜色调色板条目。 |
| isCompactPalette | boolean | 指示调色板是否紧凑。 |

### PsdColorPalette(Color[] colorPaletteEntries) {#PsdColorPalette-com.aspose.psd.Color---}
```
public PsdColorPalette(Color[] colorPaletteEntries)
```


初始化一个新的 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 类实例，并且 IsCompactPalette 为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | 颜色调色板条目。 |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---short-boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)
```


初始化一个新的 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 类实例。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | 颜色调色板条目。 |
| transparentIndex | short | 透明颜色索引。 |
| useCompactPalette | boolean | 指示调色板是否紧凑。 |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex) {#PsdColorPalette-com.aspose.psd.Color---short-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)
```


初始化一个新的 [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) 类实例，并且 IsCompactPalette 为 false。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | 颜色调色板条目。 |
| transparentIndex | short | 透明颜色索引。 |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette)
```


复制调色板。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 颜色调色板。 |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


复制调色板。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | 颜色调色板。 |
| useCompactPalette | boolean | 指示调色板是否紧凑。 |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
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
public final int getArgb32Color(int index)
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
public final int[] getArgb32Entries()
```


获取 32 位 ARGB 颜色的数组。

**Returns:**
int[] - 组成此 [ColorPalette](../../com.aspose.psd/colorpalette) 的 32 位 ARGB 结构数组。值：条目。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor(int index) {#getColor-int-}
```
public final Color getColor(int index)
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
public final Color[] getEntries()
```


获取 [Color](../../com.aspose.psd/color) 结构体的数组。

**Returns:**
com.aspose.psd.Color[] - 组成此 [ColorPalette](../../com.aspose.psd/colorpalette) 的 [Color](../../com.aspose.psd/color) 结构数组。值：条目。
### getEntriesCount() {#getEntriesCount--}
```
public final int getEntriesCount()
```


获取条目计数。

值：条目计数。

**Returns:**
int
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public final int getNearestColorIndex(Color color)
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
public final int getNearestColorIndex(int argb32Color)
```


获取最近颜色的索引。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| argb32Color | int | 32 位 ARGB 颜色。 |

**Returns:**
int - 最近颜色的索引。
### getRawEntries() {#getRawEntries--}
```
public final byte[] getRawEntries()
```


获取原始颜色调色板条目数据。

值：原始颜色调色板条目数据。

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public final int getRawEntriesCount()
```


获取原始颜色调色板条目计数。

值：原始颜色调色板条目计数。

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public final Color getTransparentColor()
```


获取透明颜色。

值：透明颜色。

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public final short getTransparentIndex()
```


获取透明颜色的索引。

值：透明颜色的索引。

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public final boolean hasTransparentColor()
```


获取一个值，指示是否存在透明颜色。

值：如果存在透明颜色，则为 true；否则，为 false。

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCompactPalette() {#isCompactPalette--}
```
public final boolean isCompactPalette()
```


获取一个值，指示调色板是否紧凑。

值：如果调色板紧凑，则为 true；否则，为 false。

--------------------

紧凑调色板意味着图像将在可能的情况下仅包含指定的调色板条目，换句话说，图像将更紧凑并占用更少的空间；否则将有 2^BitsPerPixel 条目，图像将为所有可能的调色板条目预留更多空间。将此值设为 true 并更改调色板条目可能会导致性能惩罚，因为可能会发生数据移动，请谨慎使用。

**Returns:**
boolean
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

