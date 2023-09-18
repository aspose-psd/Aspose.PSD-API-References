---
title: PsdColorPalette
second_title: Aspose.PSD for Java API Reference
description: The PSD color palette.
type: docs
weight: 13
url: /java/com.aspose.psd.fileformats.psd/psdcolorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IPsdColorPalette](../../com.aspose.psd/ipsdcolorpalette)
```
public class PsdColorPalette implements IPsdColorPalette
```

The PSD color palette.
## Constructors

| Constructor | Description |
| --- | --- |
| [PsdColorPalette(IColorPalette colorPalette)](#PsdColorPalette-com.aspose.psd.IColorPalette-) | Initializes a new instance of the [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) class. |
| [PsdColorPalette(IColorPalette colorPalette, short transparentIndex)](#PsdColorPalette-com.aspose.psd.IColorPalette-short-) | Initializes a new instance of the [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) class. |
| [PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)](#PsdColorPalette-byte---boolean-) | Initializes a new instance of the [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) class. |
| [PsdColorPalette(byte[] rawEntriesData)](#PsdColorPalette-byte---) | Initializes a new instance of the [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) class and IsCompactPalette is false. |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-byte---short-boolean-) | Initializes a new instance of the [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) class. |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex)](#PsdColorPalette-byte---short-) | Initializes a new instance of the [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) class and IsCompactPalette is false. |
| [PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)](#PsdColorPalette-int---boolean-) | Initializes a new instance of the [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) class. |
| [PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---boolean-) | Initializes a new instance of the [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) class. |
| [PsdColorPalette(Color[] colorPaletteEntries)](#PsdColorPalette-com.aspose.psd.Color---) | Initializes a new instance of the [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) class and IsCompactPalette is false. |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---short-boolean-) | Initializes a new instance of the [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) class. |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)](#PsdColorPalette-com.aspose.psd.Color---short-) | Initializes a new instance of the [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) class and IsCompactPalette is false. |
## Methods

| Method | Description |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | Copies the palette. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | Copies the palette. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Gets the 32-bit ARGB palette color by index. |
| [getArgb32Entries()](#getArgb32Entries--) | Gets an array of 32-bit ARGB colors. |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | Gets the palette color by index. |
| [getEntries()](#getEntries--) | Gets an array of [Color](../../com.aspose.psd/color) structures. |
| [getEntriesCount()](#getEntriesCount--) | Gets the entries count. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Gets the index of the nearest color. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Gets the index of the nearest color. |
| [getRawEntries()](#getRawEntries--) | Gets the raw color palette entries data. |
| [getRawEntriesCount()](#getRawEntriesCount--) | Gets the raw color palette entries count. |
| [getTransparentColor()](#getTransparentColor--) | Gets the transparent color. |
| [getTransparentIndex()](#getTransparentIndex--) | Gets the index of the transparent color. |
| [hasTransparentColor()](#hasTransparentColor--) | Gets a value indicating whether transparent color exists. |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | Gets a value indicating whether compact it palette. |
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


Initializes a new instance of the [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | The color palette. |

### PsdColorPalette(IColorPalette colorPalette, short transparentIndex) {#PsdColorPalette-com.aspose.psd.IColorPalette-short-}
```
public PsdColorPalette(IColorPalette colorPalette, short transparentIndex)
```


Initializes a new instance of the [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | The color palette. |
| transparentIndex | short | The transparent color index. |

### PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette) {#PsdColorPalette-byte---boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)
```


Initializes a new instance of the [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawEntriesData | byte[] | The raw entries data. |
| isCompactPalette | boolean | Indicating whether compact it palette. |

### PsdColorPalette(byte[] rawEntriesData) {#PsdColorPalette-byte---}
```
public PsdColorPalette(byte[] rawEntriesData)
```


Initializes a new instance of the [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) class and IsCompactPalette is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawEntriesData | byte[] | The raw entries data. |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-byte---short-boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)
```


Initializes a new instance of the [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawEntriesData | byte[] | The raw entries data. |
| transparentIndex | short | The transparent color index. Note the index is not the raw entries index instead it is for the converted color array. |
| useCompactPalette | boolean | Indicating whether compact it palette. |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex) {#PsdColorPalette-byte---short-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex)
```


Initializes a new instance of the [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) class and IsCompactPalette is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rawEntriesData | byte[] | The raw entries data. |
| transparentIndex | short | The transparent color index. Note the index is not the raw entries index instead it is for the converted color array. |

### PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette) {#PsdColorPalette-int---boolean-}
```
public PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)
```


Initializes a new instance of the [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorPaletteArgb32Entries | int[] | The color palette 32-bit ARGB entries. |
| isCompactPalette | boolean | Indicating whether compact it palette. |

### PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)
```


Initializes a new instance of the [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | The color palette entries. |
| isCompactPalette | boolean | Indicating whether compact it palette. |

### PsdColorPalette(Color[] colorPaletteEntries) {#PsdColorPalette-com.aspose.psd.Color---}
```
public PsdColorPalette(Color[] colorPaletteEntries)
```


Initializes a new instance of the [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) class and IsCompactPalette is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | The color palette entries. |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---short-boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)
```


Initializes a new instance of the [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | The color palette entries. |
| transparentIndex | short | The transparent color index. |
| useCompactPalette | boolean | Indicating whether compact it palette. |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex) {#PsdColorPalette-com.aspose.psd.Color---short-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)
```


Initializes a new instance of the [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) class and IsCompactPalette is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | The color palette entries. |
| transparentIndex | short | The transparent color index. |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette)
```


Copies the palette.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | The color palette. |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Copies the palette.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | The color palette. |
| useCompactPalette | boolean | Indicating whether compact palette. |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public final int getArgb32Color(int index)
```


Gets the 32-bit ARGB palette color by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The 32-bit ARGB palette color index. |

**Returns:**
int - The color palette entry specified by the  index .
### getArgb32Entries() {#getArgb32Entries--}
```
public final int[] getArgb32Entries()
```


Gets an array of 32-bit ARGB colors.

**Returns:**
int[] - The array of 32-bit ARGB structure that make up this [ColorPalette](../../com.aspose.psd/colorpalette). Value: The entries.
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


Gets the palette color by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The palette color index. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color palette entry specified by the  index .
### getEntries() {#getEntries--}
```
public final Color[] getEntries()
```


Gets an array of [Color](../../com.aspose.psd/color) structures.

**Returns:**
com.aspose.psd.Color[] - The array of [Color](../../com.aspose.psd/color) structure that make up this [ColorPalette](../../com.aspose.psd/colorpalette). Value: The entries.
### getEntriesCount() {#getEntriesCount--}
```
public final int getEntriesCount()
```


Gets the entries count.

Value: The entries count.

**Returns:**
int
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public final int getNearestColorIndex(Color color)
```


Gets the index of the nearest color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | The color. |

**Returns:**
int - The index of the nearest color.
### getNearestColorIndex(int argb32Color) {#getNearestColorIndex-int-}
```
public final int getNearestColorIndex(int argb32Color)
```


Gets the index of the nearest color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| argb32Color | int | The 32-bit ARGB color. |

**Returns:**
int - The index of the nearest color.
### getRawEntries() {#getRawEntries--}
```
public final byte[] getRawEntries()
```


Gets the raw color palette entries data.

Value: The raw color palette entries data.

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public final int getRawEntriesCount()
```


Gets the raw color palette entries count.

Value: The raw color palette entries count.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public final Color getTransparentColor()
```


Gets the transparent color.

Value: The transparent color.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public final short getTransparentIndex()
```


Gets the index of the transparent color.

Value: The index of the transparent color.

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public final boolean hasTransparentColor()
```


Gets a value indicating whether transparent color exists.

Value:  true  if transparent color exists; otherwise,  false .

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


Gets a value indicating whether compact it palette.

Value:  true  if compact it palette; otherwise,  false .

--------------------

Compact palette means that image will contain only the specified palette entries if possible or in other words the image will be more compact and occupy less space; otherwise there will be 2^BitsPerPixel entries and image will reserve more space for all possible palette entries. Setting this value to true and changing palette entries may cause performance penalty since data movement may occur so use it carefully.

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
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

