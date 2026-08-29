---
title: "IPsdColorPalette"
second_title: "Aspose.PSD för Java API-referens"
description: "Den pasd-färgpaletten"
type: docs
weight: 134
url: /sv/java/com.aspose.psd/ipsdcolorpalette/
---

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public interface IPsdColorPalette extends IColorPalette
```

Den pasd-färgpaletten
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRawEntries()](#getRawEntries--) | Hämtar de råa data för färgpalettens poster. |
| [getRawEntriesCount()](#getRawEntriesCount--) | Hämtar antalet råa färgpalettposter. |
| [getTransparentColor()](#getTransparentColor--) | Hämtar den transparenta färgen. |
| [getTransparentIndex()](#getTransparentIndex--) | Hämtar indexet för den transparenta färgen. |
| [hasTransparentColor()](#hasTransparentColor--) | Hämtar ett värde som indikerar om en transparent färg finns. |
### getRawEntries() {#getRawEntries--}
```
public abstract byte[] getRawEntries()
```


Hämtar de råa data för färgpalettens poster.

Värde: De råa färgpalettposternas data.

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public abstract int getRawEntriesCount()
```


Hämtar antalet råa färgpalettposter.

Värde: Antalet råa färgpalettposter.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public abstract Color getTransparentColor()
```


Hämtar den transparenta färgen.

Värde: Den transparenta färgen.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public abstract short getTransparentIndex()
```


Hämtar indexet för den transparenta färgen.

Värde: Indexet för den transparenta färgen.

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public abstract boolean hasTransparentColor()
```


Hämtar ett värde som indikerar om en transparent färg finns.

Värde:  true  om transparent färg finns; annars,  false .

**Returns:**
boolean
