---
title: "Färgpalett"
second_title: "Aspose.PSD för Java API-referens"
description: "Definierar en array av färger som utgör en färgpalett."
type: docs
weight: 27
url: /sv/java/com.aspose.psd/colorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public final class ColorPalette implements IColorPalette
```

Definierar en array av färger som utgör en färgpalett. Färgerna är 32-bitars ARGB-färger. Ej ärftlig.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ColorPalette(int[] argb32Entries, boolean isCompactPalette)](#ColorPalette-int---boolean-) | Initierar en ny instans av  ColorPalette  klassen. |
| [ColorPalette(int[] argb32Entries)](#ColorPalette-int---) | Initierar en ny instans av  ColorPalette  klassen och IsCompactPalette är falskt. |
| [ColorPalette(Color[] entries, boolean isCompactPalette)](#ColorPalette-com.aspose.psd.Color---boolean-) | Initierar en ny instans av  ColorPalette  klassen. |
| [ColorPalette(Color[] entries)](#ColorPalette-com.aspose.psd.Color---) | Initierar en ny instans av  ColorPalette  klassen och IsCompactPalette är falskt. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | Kopierar paletten. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | Kopierar paletten. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Hämtar 32‑bitars ARGB‑palettfärgen efter index. |
| [getArgb32Entries()](#getArgb32Entries--) | Hämtar en array av 32-bitars ARGB-strukturer. |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | Hämtar palettfärgen efter index. |
| [getEntries()](#getEntries--) | Hämtar en array av  com.aspose.psd.Color  strukturer. |
| [getEntriesCount()](#getEntriesCount--) | Hämtar antalet poster. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Hämtar indexet för den närmaste färgen. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Hämtar indexet för den närmaste färgen. |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | Hämtar eller anger ett värde som indikerar om kompakt palett används. |
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


Initierar en ny instans av  ColorPalette  klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argb32Entries | int[] | De 32-bitars ARGB-färgpalettposterna. |
| isCompactPalette | boolean | Indikerar om paletten är kompakt. |

### ColorPalette(int[] argb32Entries) {#ColorPalette-int---}
```
public ColorPalette(int[] argb32Entries)
```


Initierar en ny instans av  ColorPalette  klassen och IsCompactPalette är falskt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argb32Entries | int[] | De 32-bitars ARGB-färgpalettposterna. |

### ColorPalette(Color[] entries, boolean isCompactPalette) {#ColorPalette-com.aspose.psd.Color---boolean-}
```
public ColorPalette(Color[] entries, boolean isCompactPalette)
```


Initierar en ny instans av  ColorPalette  klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | Färgpalettens poster. |
| isCompactPalette | boolean | Indikerar om paletten är kompakt. |

### ColorPalette(Color[] entries) {#ColorPalette-com.aspose.psd.Color---}
```
public ColorPalette(Color[] entries)
```


Initierar en ny instans av  ColorPalette  klassen och IsCompactPalette är falskt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | Färgpalettens poster. |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette)
```


Kopierar paletten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Färgpaletten. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Kopierar paletten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Färgpaletten. |
| useCompactPalette | boolean | Indikerar om paletten är kompakt. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
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
public int getArgb32Color(int index)
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
public int[] getArgb32Entries()
```


Hämtar en array av 32-bitars ARGB-strukturer.

**Returns:**
int[] - Posterna. Arrayen av 32-bitars ARGB-struktur som utgör denna  Aspose.Imaging.ColorPalette .
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


Hämtar palettfärgen efter index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Palettens färgindex. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color palette entry specified by the  index .
### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


Hämtar en array av  com.aspose.psd.Color  strukturer.

**Returns:**
com.aspose.psd.Color[] - Posterna. Arrayen av  com.aspose.psd.Color  struktur som utgör denna  Aspose.Imaging.ColorPalette .
### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


Hämtar antalet poster.

**Returns:**
int - Antalet poster.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public int getNearestColorIndex(Color color)
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
public int getNearestColorIndex(int argb32Color)
```


Hämtar indexet för den närmaste färgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argb32Color | int | Den 32-bitars ARGB-färgen. |

**Returns:**
int - Indexet för den närmaste färgen.
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


Hämtar eller anger ett värde som indikerar om kompakt palett används.

**Returns:**
boolean -  true  om kompakt palett används; annars  false .

Kompakt palett betyder att bilden endast kommer att innehålla de angivna palettposterna om möjligt, eller med andra ord blir bilden mer kompakt och upptar mindre utrymme; annars kommer det att finnas 2^BitsPerPixel poster och bilden reserverar mer utrymme för alla möjliga palettposter. Att sätta detta värde till true och ändra palettposter kan medföra prestandapåverkan eftersom dataförflyttning kan inträffa, så använd det försiktigt.
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

