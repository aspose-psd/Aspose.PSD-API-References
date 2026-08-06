---
title: "IColorPalette"
second_title: "Aspose.PSD 的 Java API 参考"
description: "颜色调色板接口。"
type: docs
weight: 117
url: /zh/java/com.aspose.psd/icolorpalette/
---
```
public interface IColorPalette
```

颜色调色板接口。
## Methods

| Method | 描述 |
| --- | --- |
| [getArgb32Color(int index)](#getArgb32Color-int-) | 根据索引获取 32 位 ARGB 调色板颜色。 |
| [getArgb32Entries()](#getArgb32Entries--) | 获取 32 位 ARGB 结构的数组。 |
| [getColor(int index)](#getColor-int-) | 根据索引获取调色板颜色。 |
| [getEntries()](#getEntries--) | 获取 com.aspose.psd.Color 结构的数组。 |
| [getEntriesCount()](#getEntriesCount--) | 获取条目计数。 |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | 获取最近颜色的索引。 |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | 获取最近的 32 位 ARGB 颜色的索引。 |
| [isCompactPalette()](#isCompactPalette--) | 获取一个值，指示是否使用紧凑调色板。 |
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public abstract int getArgb32Color(int index)
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
public abstract int[] getArgb32Entries()
```


获取 32 位 ARGB 结构的数组。

**Returns:**
int[] - 32 位 ARGB 条目。构成此 com.aspose.psd.ColorPalette 的 32 位 ARGB 结构数组。
### getColor(int index) {#getColor-int-}
```
public abstract Color getColor(int index)
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
public abstract Color[] getEntries()
```


获取 com.aspose.psd.Color 结构的数组。

**Returns:**
com.aspose.psd.Color[] - 条目。构成此 com.aspose.psd.ColorPalette 的 com.aspose.psd.Color 结构数组。
### getEntriesCount() {#getEntriesCount--}
```
public abstract int getEntriesCount()
```


获取条目计数。

**Returns:**
int - 条目计数。
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public abstract int getNearestColorIndex(Color color)
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
public abstract int getNearestColorIndex(int argb32Color)
```


获取最近的 32 位 ARGB 颜色的索引。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| argb32Color | int | 32 位 ARGB 颜色。 |

**Returns:**
int - 最近颜色的索引。
### isCompactPalette() {#isCompactPalette--}
```
public abstract boolean isCompactPalette()
```


获取一个值，指示是否使用紧凑调色板。

紧凑调色板意味着图像将在可能的情况下仅包含指定的调色板条目，换句话说，图像将更紧凑并占用更少的空间；否则将有 2^BitsPerPixel 条目，图像将为所有可能的调色板条目预留更多空间。将此值设为 true 并更改调色板条目可能会导致性能惩罚，因为可能会发生数据移动，请谨慎使用。

**Returns:**
布尔型 - 如果使用紧凑调色板则为 true；否则为 false。
