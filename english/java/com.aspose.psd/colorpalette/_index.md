---
title: ColorPalette
second_title: Aspose.PSD for Java API Reference
description: Defines an array of colors that make up a color palette.
type: docs
weight: 27
url: /java/com.aspose.psd/colorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public final class ColorPalette implements IColorPalette
```

Defines an array of colors that make up a color palette. The colors are 32-bit ARGB colors. Not inheritable.
## Constructors

| Constructor | Description |
| --- | --- |
| [ColorPalette(int[] argb32Entries, boolean isCompactPalette)](#ColorPalette-int---boolean-) | Initializes a new instance of the  ColorPalette  class. |
| [ColorPalette(int[] argb32Entries)](#ColorPalette-int---) | Initializes a new instance of the  ColorPalette  class and IsCompactPalette is false. |
| [ColorPalette(Color[] entries, boolean isCompactPalette)](#ColorPalette-com.aspose.psd.Color---boolean-) | Initializes a new instance of the  ColorPalette  class. |
| [ColorPalette(Color[] entries)](#ColorPalette-com.aspose.psd.Color---) | Initializes a new instance of the  ColorPalette  class and IsCompactPalette is false. |
## Methods

| Method | Description |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | Copies the palette. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | Copies the palette. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Gets the 32-bit ARGB palette color by index. |
| [getArgb32Entries()](#getArgb32Entries--) | Gets an array of 32-bit ARGB structures. |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | Gets the palette color by index. |
| [getEntries()](#getEntries--) | Gets an array of  com.aspose.psd.Color  structures. |
| [getEntriesCount()](#getEntriesCount--) | Gets the entries count. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Gets the index of the nearest color. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Gets the index of the nearest color. |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | Gets or sets a value indicating whether compact palette is used. |
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


Initializes a new instance of the  ColorPalette  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| argb32Entries | int[] | The 32-bit ARGB color palette entries. |
| isCompactPalette | boolean | Indicating whether compact it palette. |

### ColorPalette(int[] argb32Entries) {#ColorPalette-int---}
```
public ColorPalette(int[] argb32Entries)
```


Initializes a new instance of the  ColorPalette  class and IsCompactPalette is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| argb32Entries | int[] | The 32-bit ARGB color palette entries. |

### ColorPalette(Color[] entries, boolean isCompactPalette) {#ColorPalette-com.aspose.psd.Color---boolean-}
```
public ColorPalette(Color[] entries, boolean isCompactPalette)
```


Initializes a new instance of the  ColorPalette  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | The color palette entries. |
| isCompactPalette | boolean | Indicating whether compact it palette. |

### ColorPalette(Color[] entries) {#ColorPalette-com.aspose.psd.Color---}
```
public ColorPalette(Color[] entries)
```


Initializes a new instance of the  ColorPalette  class and IsCompactPalette is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | The color palette entries. |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette)
```


Copies the palette.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | The color palette. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Copies the palette.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | The color palette. |
| useCompactPalette | boolean | Indicating whether compact palette. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
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
public int getArgb32Color(int index)
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
public int[] getArgb32Entries()
```


Gets an array of 32-bit ARGB structures.

**Returns:**
int[] - The entries. The array of 32-bit ARGB structure that make up this  Aspose.Imaging.ColorPalette .
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


Gets the palette color by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The palette color index. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color palette entry specified by the  index .
### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


Gets an array of  com.aspose.psd.Color  structures.

**Returns:**
com.aspose.psd.Color[] - The entries. The array of  com.aspose.psd.Color  structure that make up this  Aspose.Imaging.ColorPalette .
### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


Gets the entries count.

**Returns:**
int - The entries count.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public int getNearestColorIndex(Color color)
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
public int getNearestColorIndex(int argb32Color)
```


Gets the index of the nearest color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| argb32Color | int | The 32-bit ARGB color. |

**Returns:**
int - The index of the nearest color.
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


Gets or sets a value indicating whether compact palette is used.

**Returns:**
boolean -  true  if compact palette is used; otherwise,  false .

Compact palette means that image will contain only the specified palette entries if possible or in other words the image will be more compact and occupy less space; otherwise there will be 2^BitsPerPixel entries and image will reserve more space for all possible palette entries. Setting this value to true and changing palette entries may cause performance penalty since data movement may occur so use it carefully.
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

