---
title: "IColorPalette"
second_title: "Aspose.PSD för Java API-referens"
description: "Gränssnittet för färgpalett."
type: docs
weight: 117
url: /sv/java/com.aspose.psd/icolorpalette/
---
```
public interface IColorPalette
```

Gränssnittet för färgpalett.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Hämtar 32‑bitars ARGB‑palettfärgen efter index. |
| [getArgb32Entries()](#getArgb32Entries--) | Hämtar en array av 32-bitars ARGB-strukturer. |
| [getColor(int index)](#getColor-int-) | Hämtar palettfärgen efter index. |
| [getEntries()](#getEntries--) | Hämtar en array av  com.aspose.psd.Color  strukturer. |
| [getEntriesCount()](#getEntriesCount--) | Hämtar antalet poster. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Hämtar indexet för den närmaste färgen. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Hämtar indexet för den närmaste 32-bitars ARGB-färgen. |
| [isCompactPalette()](#isCompactPalette--) | Hämtar ett värde som indikerar om kompakt palett används. |
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public abstract int getArgb32Color(int index)
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
public abstract int[] getArgb32Entries()
```


Hämtar en array av 32-bitars ARGB-strukturer.

**Returns:**
int[] - De 32-bitars ARGB-posterna. Arrayen av 32-bitars ARGB-struktur som utgör denna  com.aspose.psd.ColorPalette .
### getColor(int index) {#getColor-int-}
```
public abstract Color getColor(int index)
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
public abstract Color[] getEntries()
```


Hämtar en array av  com.aspose.psd.Color  strukturer.

**Returns:**
com.aspose.psd.Color[] - Posterna. Arrayen av  com.aspose.psd.Color  struktur som utgör denna  com.aspose.psd.ColorPalette .
### getEntriesCount() {#getEntriesCount--}
```
public abstract int getEntriesCount()
```


Hämtar antalet poster.

**Returns:**
int - Antalet poster.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public abstract int getNearestColorIndex(Color color)
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
public abstract int getNearestColorIndex(int argb32Color)
```


Hämtar indexet för den närmaste 32-bitars ARGB-färgen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| argb32Color | int | Den 32-bitars ARGB-färgen. |

**Returns:**
int - Indexet för den närmaste färgen.
### isCompactPalette() {#isCompactPalette--}
```
public abstract boolean isCompactPalette()
```


Hämtar ett värde som indikerar om kompakt palett används.

Kompakt palett betyder att bilden endast kommer att innehålla de angivna palettposterna om möjligt, eller med andra ord blir bilden mer kompakt och upptar mindre utrymme; annars kommer det att finnas 2^BitsPerPixel poster och bilden reserverar mer utrymme för alla möjliga palettposter. Att sätta detta värde till true och ändra palettposter kan medföra prestandapåverkan eftersom dataförflyttning kan inträffa, så använd det försiktigt.

**Returns:**
boolean -  true  om kompakt palett används; annars  false .
