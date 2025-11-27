---
title: IPsdColorPalette
second_title: Aspose.PSD for Java API Reference
description: The pasd color palette
type: docs
weight: 134
url: /java/com.aspose.psd/ipsdcolorpalette/
---

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public interface IPsdColorPalette extends IColorPalette
```

The pasd color palette
## Methods

| Method | Description |
| --- | --- |
| [getRawEntries()](#getRawEntries--) | Gets the raw color palette entries data. |
| [getRawEntriesCount()](#getRawEntriesCount--) | Gets the raw color palette entries count. |
| [getTransparentColor()](#getTransparentColor--) | Gets the transparent color. |
| [getTransparentIndex()](#getTransparentIndex--) | Gets the index of the transparent color. |
| [hasTransparentColor()](#hasTransparentColor--) | Gets a value indicating whether transparent color exists. |
### getRawEntries() {#getRawEntries--}
```
public abstract byte[] getRawEntries()
```


Gets the raw color palette entries data.

Value: The raw color palette entries data.

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public abstract int getRawEntriesCount()
```


Gets the raw color palette entries count.

Value: The raw color palette entries count.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public abstract Color getTransparentColor()
```


Gets the transparent color.

Value: The transparent color.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public abstract short getTransparentIndex()
```


Gets the index of the transparent color.

Value: The index of the transparent color.

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public abstract boolean hasTransparentColor()
```


Gets a value indicating whether transparent color exists.

Value:  true  if transparent color exists; otherwise,  false .

**Returns:**
boolean
