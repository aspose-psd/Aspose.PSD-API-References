---
title: "IPsdColorPalette"
second_title: "Aspose.PSD 的 Java API 参考"
description: "pasd 颜色调色板"
type: docs
weight: 134
url: /zh/java/com.aspose.psd/ipsdcolorpalette/
---

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public interface IPsdColorPalette extends IColorPalette
```

pasd 颜色调色板
## Methods

| Method | 描述 |
| --- | --- |
| [getRawEntries()](#getRawEntries--) | 获取原始颜色调色板条目数据。 |
| [getRawEntriesCount()](#getRawEntriesCount--) | 获取原始颜色调色板条目计数。 |
| [getTransparentColor()](#getTransparentColor--) | 获取透明颜色。 |
| [getTransparentIndex()](#getTransparentIndex--) | 获取透明颜色的索引。 |
| [hasTransparentColor()](#hasTransparentColor--) | 获取一个值，指示是否存在透明颜色。 |
### getRawEntries() {#getRawEntries--}
```
public abstract byte[] getRawEntries()
```


获取原始颜色调色板条目数据。

值：原始颜色调色板条目数据。

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public abstract int getRawEntriesCount()
```


获取原始颜色调色板条目计数。

值：原始颜色调色板条目计数。

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public abstract Color getTransparentColor()
```


获取透明颜色。

值：透明颜色。

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public abstract short getTransparentIndex()
```


获取透明颜色的索引。

值：透明颜色的索引。

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public abstract boolean hasTransparentColor()
```


获取一个值，指示是否存在透明颜色。

值：如果存在透明颜色，则为 true；否则，为 false。

**Returns:**
boolean
