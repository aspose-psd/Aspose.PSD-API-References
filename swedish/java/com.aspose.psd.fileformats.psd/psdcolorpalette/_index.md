---
title: "PsdColorPalette"
second_title: "Aspose.PSD för Java API-referens"
description: "PSD-färgpaletten."
type: docs
weight: 13
url: /sv/java/com.aspose.psd.fileformats.psd/psdcolorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IPsdColorPalette](../../com.aspose.psd/ipsdcolorpalette)
```
public class PsdColorPalette implements IPsdColorPalette
```

PSD-färgpaletten.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PsdColorPalette(IColorPalette colorPalette)](#PsdColorPalette-com.aspose.psd.IColorPalette-) | Initierar en ny instans av klassen [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(IColorPalette colorPalette, short transparentIndex)](#PsdColorPalette-com.aspose.psd.IColorPalette-short-) | Initierar en ny instans av klassen [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)](#PsdColorPalette-byte---boolean-) | Initierar en ny instans av klassen [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(byte[] rawEntriesData)](#PsdColorPalette-byte---) | Initierar en ny instans av klassen [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) och IsCompactPalette är falskt. |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-byte---short-boolean-) | Initierar en ny instans av klassen [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex)](#PsdColorPalette-byte---short-) | Initierar en ny instans av klassen [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) och IsCompactPalette är falskt. |
| [PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)](#PsdColorPalette-int---boolean-) | Initierar en ny instans av klassen [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---boolean-) | Initierar en ny instans av klassen [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(Color[] colorPaletteEntries)](#PsdColorPalette-com.aspose.psd.Color---) | Initierar en ny instans av klassen [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) och IsCompactPalette är falskt. |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---short-boolean-) | Initierar en ny instans av klassen [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)](#PsdColorPalette-com.aspose.psd.Color---short-) | Initierar en ny instans av klassen [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) och IsCompactPalette är falskt. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | Kopierar paletten. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | Kopierar paletten. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Hämtar 32‑bitars ARGB‑palettfärgen efter index. |
| [getArgb32Entries()](#getArgb32Entries--) | Hämtar en array av 32‑bitars ARGB‑färger. |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | Hämtar palettfärgen efter index. |
| [getEntries()](#getEntries--) | Hämtar en array av strukturerna [Color](../../com.aspose.psd/color). |
| [getEntriesCount()](#getEntriesCount--) | Hämtar antalet poster. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Hämtar indexet för den närmaste färgen. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Hämtar indexet för den närmaste färgen. |
| [getRawEntries()](#getRawEntries--) | Hämtar de råa data för färgpalettens poster. |
| [getRawEntriesCount()](#getRawEntriesCount--) | Hämtar antalet råa färgpalettposter. |
| [getTransparentColor()](#getTransparentColor--) | Hämtar den transparenta färgen. |
| [getTransparentIndex()](#getTransparentIndex--) | Hämtar indexet för den transparenta färgen. |
| [hasTransparentColor()](#hasTransparentColor--) | Hämtar ett värde som indikerar om en transparent färg finns. |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | Hämtar ett värde som indikerar om paletten är kompakt. |
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


Initierar en ny instans av klassen [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Färgpaletten. |

### PsdColorPalette(IColorPalette colorPalette, short transparentIndex) {#PsdColorPalette-com.aspose.psd.IColorPalette-short-}
```
public PsdColorPalette(IColorPalette colorPalette, short transparentIndex)
```


Initierar en ny instans av klassen [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Färgpaletten. |
| transparentIndex | short | Det transparenta färgindexet. |

### PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette) {#PsdColorPalette-byte---boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)
```


Initierar en ny instans av klassen [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rawEntriesData | byte[] | De råa posternas data. |
| isCompactPalette | boolean | Indikerar om paletten är kompakt. |

### PsdColorPalette(byte[] rawEntriesData) {#PsdColorPalette-byte---}
```
public PsdColorPalette(byte[] rawEntriesData)
```


Initierar en ny instans av klassen [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) och IsCompactPalette är falskt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rawEntriesData | byte[] | De råa posternas data. |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-byte---short-boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)
```


Initierar en ny instans av klassen [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rawEntriesData | byte[] | De råa posternas data. |
| transparentIndex | short | Det transparenta färgindexet. Observera att indexet inte är det råa postindexet utan är för den konverterade färgarrayen. |
| useCompactPalette | boolean | Indikerar om paletten är kompakt. |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex) {#PsdColorPalette-byte---short-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex)
```


Initierar en ny instans av klassen [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) och IsCompactPalette är falskt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rawEntriesData | byte[] | De råa posternas data. |
| transparentIndex | short | Det transparenta färgindexet. Observera att indexet inte är det råa postindexet utan är för den konverterade färgarrayen. |

### PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette) {#PsdColorPalette-int---boolean-}
```
public PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)
```


Initierar en ny instans av klassen [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorPaletteArgb32Entries | int[] | Färgpalettens 32-bitars ARGB-poster. |
| isCompactPalette | boolean | Indikerar om paletten är kompakt. |

### PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)
```


Initierar en ny instans av klassen [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Färgpalettens poster. |
| isCompactPalette | boolean | Indikerar om paletten är kompakt. |

### PsdColorPalette(Color[] colorPaletteEntries) {#PsdColorPalette-com.aspose.psd.Color---}
```
public PsdColorPalette(Color[] colorPaletteEntries)
```


Initierar en ny instans av klassen [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) och IsCompactPalette är falskt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Färgpalettens poster. |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---short-boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)
```


Initierar en ny instans av klassen [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Färgpalettens poster. |
| transparentIndex | short | Det transparenta färgindexet. |
| useCompactPalette | boolean | Indikerar om paletten är kompakt. |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex) {#PsdColorPalette-com.aspose.psd.Color---short-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)
```


Initierar en ny instans av klassen [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) och IsCompactPalette är falskt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Färgpalettens poster. |
| transparentIndex | short | Det transparenta färgindexet. |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette)
```


Kopierar paletten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Färgpaletten. |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Kopierar paletten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Färgpaletten. |
| useCompactPalette | boolean | Indikerar om paletten är kompakt. |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public final int getArgb32Color(int index)
```


Hämtar 32‑bitars ARGB‑palettfärgen efter index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det 32-bitars ARGB-palettfärgindexet. |

**Returns:**
int - Färgpalettposten som specificeras av indexet.
### getArgb32Entries() {#getArgb32Entries--}
```
public final int[] getArgb32Entries()
```


Hämtar en array av 32‑bitars ARGB‑färger.

**Returns:**
int[] - Arrayen av 32-bitars ARGB-strukturer som utgör denna [ColorPalette](../../com.aspose.psd/colorpalette). Värde: Poster.
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


Hämtar palettfärgen efter index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Palettens färgindex. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color palette entry specified by the  index .
### getEntries() {#getEntries--}
```
public final Color[] getEntries()
```


Hämtar en array av strukturerna [Color](../../com.aspose.psd/color).

**Returns:**
com.aspose.psd.Color[] - Arrayen av [Color](../../com.aspose.psd/color)-struktur som utgör denna [ColorPalette](../../com.aspose.psd/colorpalette). Värde: Poster.
### getEntriesCount() {#getEntriesCount--}
```
public final int getEntriesCount()
```


Hämtar antalet poster.

Värde: Antalet poster.

**Returns:**
int
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public final int getNearestColorIndex(Color color)
```


Hämtar indexet för den närmaste färgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Färgen. |

**Returns:**
int - Indexet för den närmaste färgen.
### getNearestColorIndex(int argb32Color) {#getNearestColorIndex-int-}
```
public final int getNearestColorIndex(int argb32Color)
```


Hämtar indexet för den närmaste färgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argb32Color | int | Den 32-bitars ARGB-färgen. |

**Returns:**
int - Indexet för den närmaste färgen.
### getRawEntries() {#getRawEntries--}
```
public final byte[] getRawEntries()
```


Hämtar de råa data för färgpalettens poster.

Värde: De råa färgpalettposternas data.

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public final int getRawEntriesCount()
```


Hämtar antalet råa färgpalettposter.

Värde: Antalet råa färgpalettposter.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public final Color getTransparentColor()
```


Hämtar den transparenta färgen.

Värde: Den transparenta färgen.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public final short getTransparentIndex()
```


Hämtar indexet för den transparenta färgen.

Värde: Indexet för den transparenta färgen.

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public final boolean hasTransparentColor()
```


Hämtar ett värde som indikerar om en transparent färg finns.

Värde:  true  om transparent färg finns; annars,  false .

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


Hämtar ett värde som indikerar om paletten är kompakt.

Värde:  true  om kompakt palett; annars,  false .

--------------------

Kompakt palett betyder att bilden endast kommer att innehålla de angivna palettposterna om möjligt, eller med andra ord blir bilden mer kompakt och upptar mindre utrymme; annars kommer det att finnas 2^BitsPerPixel poster och bilden reserverar mer utrymme för alla möjliga palettposter. Att sätta detta värde till true och ändra palettposter kan medföra prestandapåverkan eftersom dataförflyttning kan inträffa, så använd det försiktigt.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

