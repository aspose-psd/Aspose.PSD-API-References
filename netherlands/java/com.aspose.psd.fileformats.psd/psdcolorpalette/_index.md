---
title: "PsdColorPalette"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Het PSD-kleurenpalet."
type: docs
weight: 13
url: /nl/java/com.aspose.psd.fileformats.psd/psdcolorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IPsdColorPalette](../../com.aspose.psd/ipsdcolorpalette)
```
public class PsdColorPalette implements IPsdColorPalette
```

Het PSD-kleurenpalet.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PsdColorPalette(IColorPalette colorPalette)](#PsdColorPalette-com.aspose.psd.IColorPalette-) | Initialiseert een nieuw exemplaar van de [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) klasse. |
| [PsdColorPalette(IColorPalette colorPalette, short transparentIndex)](#PsdColorPalette-com.aspose.psd.IColorPalette-short-) | Initialiseert een nieuw exemplaar van de [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) klasse. |
| [PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)](#PsdColorPalette-byte---boolean-) | Initialiseert een nieuw exemplaar van de [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) klasse. |
| [PsdColorPalette(byte[] rawEntriesData)](#PsdColorPalette-byte---) | Initialiseert een nieuw exemplaar van de [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) klasse en IsCompactPalette is false. |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-byte---short-boolean-) | Initialiseert een nieuw exemplaar van de [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) klasse. |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex)](#PsdColorPalette-byte---short-) | Initialiseert een nieuw exemplaar van de [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) klasse en IsCompactPalette is false. |
| [PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)](#PsdColorPalette-int---boolean-) | Initialiseert een nieuw exemplaar van de [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) klasse. |
| [PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---boolean-) | Initialiseert een nieuw exemplaar van de [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) klasse. |
| [PsdColorPalette(Color[] colorPaletteEntries)](#PsdColorPalette-com.aspose.psd.Color---) | Initialiseert een nieuw exemplaar van de [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) klasse en IsCompactPalette is false. |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---short-boolean-) | Initialiseert een nieuw exemplaar van de [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) klasse. |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)](#PsdColorPalette-com.aspose.psd.Color---short-) | Initialiseert een nieuw exemplaar van de [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) klasse en IsCompactPalette is false. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | Kopieert de palet. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | Kopieert de palet. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Haalt de 32-bit ARGB-paletkleur op op basis van index. |
| [getArgb32Entries()](#getArgb32Entries--) | Haalt een array van 32-bit ARGB-kleuren op. |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | Haalt de paletkleur op op basis van index. |
| [getEntries()](#getEntries--) | Haalt een array van [Color](../../com.aspose.psd/color) structuren op. |
| [getEntriesCount()](#getEntriesCount--) | Haalt het aantal items op. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Haalt de index van de dichtstbijzijnde kleur op. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Haalt de index van de dichtstbijzijnde kleur op. |
| [getRawEntries()](#getRawEntries--) | Haalt de ruwe gegevens van de kleurpaletinvoer op. |
| [getRawEntriesCount()](#getRawEntriesCount--) | Haalt het aantal ruwe kleurpaletinvoer op. |
| [getTransparentColor()](#getTransparentColor--) | Haalt de transparante kleur op. |
| [getTransparentIndex()](#getTransparentIndex--) | Haalt de index van de transparante kleur op. |
| [hasTransparentColor()](#hasTransparentColor--) | Haalt een waarde op die aangeeft of een transparante kleur bestaat. |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | Haalt een waarde op die aangeeft of het palet compact is. |
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


Initialiseert een nieuw exemplaar van de [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Het kleurenpalet. |

### PsdColorPalette(IColorPalette colorPalette, short transparentIndex) {#PsdColorPalette-com.aspose.psd.IColorPalette-short-}
```
public PsdColorPalette(IColorPalette colorPalette, short transparentIndex)
```


Initialiseert een nieuw exemplaar van de [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Het kleurenpalet. |
| transparentIndex | short | De index van de transparante kleur. |

### PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette) {#PsdColorPalette-byte---boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)
```


Initialiseert een nieuw exemplaar van de [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rawEntriesData | byte[] | De ruwe invoergegevens. |
| isCompactPalette | boolean | Geeft aan of het palet compact is. |

### PsdColorPalette(byte[] rawEntriesData) {#PsdColorPalette-byte---}
```
public PsdColorPalette(byte[] rawEntriesData)
```


Initialiseert een nieuw exemplaar van de [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) klasse en IsCompactPalette is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rawEntriesData | byte[] | De ruwe invoergegevens. |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-byte---short-boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)
```


Initialiseert een nieuw exemplaar van de [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rawEntriesData | byte[] | De ruwe invoergegevens. |
| transparentIndex | short | De index van de transparante kleur. Opmerking: de index is niet de index van de ruwe invoer, maar die van de geconverteerde kleurenarray. |
| useCompactPalette | boolean | Geeft aan of het palet compact is. |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex) {#PsdColorPalette-byte---short-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex)
```


Initialiseert een nieuw exemplaar van de [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) klasse en IsCompactPalette is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rawEntriesData | byte[] | De ruwe invoergegevens. |
| transparentIndex | short | De index van de transparante kleur. Opmerking: de index is niet de index van de ruwe invoer, maar die van de geconverteerde kleurenarray. |

### PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette) {#PsdColorPalette-int---boolean-}
```
public PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)
```


Initialiseert een nieuw exemplaar van de [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| colorPaletteArgb32Entries | int[] | De 32‑bit ARGB‑invoeren van het kleurpalet. |
| isCompactPalette | boolean | Geeft aan of het palet compact is. |

### PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)
```


Initialiseert een nieuw exemplaar van de [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | De invoeren van het kleurpalet. |
| isCompactPalette | boolean | Geeft aan of het palet compact is. |

### PsdColorPalette(Color[] colorPaletteEntries) {#PsdColorPalette-com.aspose.psd.Color---}
```
public PsdColorPalette(Color[] colorPaletteEntries)
```


Initialiseert een nieuw exemplaar van de [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) klasse en IsCompactPalette is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | De invoeren van het kleurpalet. |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---short-boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)
```


Initialiseert een nieuw exemplaar van de [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | De invoeren van het kleurpalet. |
| transparentIndex | short | De index van de transparante kleur. |
| useCompactPalette | boolean | Geeft aan of het palet compact is. |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex) {#PsdColorPalette-com.aspose.psd.Color---short-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)
```


Initialiseert een nieuw exemplaar van de [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) klasse en IsCompactPalette is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | De invoeren van het kleurpalet. |
| transparentIndex | short | De index van de transparante kleur. |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette)
```


Kopieert de palet.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Het kleurenpalet. |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Kopieert de palet.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Het kleurenpalet. |
| useCompactPalette | boolean | Geeft aan of het palet compact is. |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public final int getArgb32Color(int index)
```


Haalt de 32-bit ARGB-paletkleur op op basis van index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De 32‑bit ARGB‑kleurindex van het palet. |

**Returns:**
int - De kleurpaletinvoer gespecificeerd door de index.
### getArgb32Entries() {#getArgb32Entries--}
```
public final int[] getArgb32Entries()
```


Haalt een array van 32-bit ARGB-kleuren op.

**Returns:**
int[] - De array van 32‑bit ARGB‑structuren die deze [ColorPalette](../../com.aspose.psd/colorpalette) vormen. Waarde: de invoeren.
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


Haalt de paletkleur op op basis van index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De paletkleurindex. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color palette entry specified by the  index .
### getEntries() {#getEntries--}
```
public final Color[] getEntries()
```


Haalt een array van [Color](../../com.aspose.psd/color) structuren op.

**Returns:**
com.aspose.psd.Color[] - De array van [Color](../../com.aspose.psd/color) structuren die deze [ColorPalette](../../com.aspose.psd/colorpalette) vormen. Waarde: de invoeren.
### getEntriesCount() {#getEntriesCount--}
```
public final int getEntriesCount()
```


Haalt het aantal items op.

Waarde: het aantal invoeren.

**Returns:**
int
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public final int getNearestColorIndex(Color color)
```


Haalt de index van de dichtstbijzijnde kleur op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | De kleur. |

**Returns:**
int - De index van de dichtstbijzijnde kleur.
### getNearestColorIndex(int argb32Color) {#getNearestColorIndex-int-}
```
public final int getNearestColorIndex(int argb32Color)
```


Haalt de index van de dichtstbijzijnde kleur op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| argb32Color | int | De 32-bit ARGB-kleur. |

**Returns:**
int - De index van de dichtstbijzijnde kleur.
### getRawEntries() {#getRawEntries--}
```
public final byte[] getRawEntries()
```


Haalt de ruwe gegevens van de kleurpaletinvoer op.

Value: De ruwe gegevens van de kleurenpaletitems.

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public final int getRawEntriesCount()
```


Haalt het aantal ruwe kleurpaletinvoer op.

Value: Het ruwe aantal kleurenpaletitems.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public final Color getTransparentColor()
```


Haalt de transparante kleur op.

Value: De transparante kleur.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public final short getTransparentIndex()
```


Haalt de index van de transparante kleur op.

Value: De index van de transparante kleur.

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public final boolean hasTransparentColor()
```


Haalt een waarde op die aangeeft of een transparante kleur bestaat.

Value:  true  als er een transparante kleur bestaat; anders,  false .

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


Haalt een waarde op die aangeeft of het palet compact is.

Value:  true  als het palet compact is; anders,  false .

--------------------

Een compact palet betekent dat de afbeelding alleen de opgegeven paletitems bevat indien mogelijk, of met andere woorden, de afbeelding compacter is en minder ruimte inneemt; anders zullen er 2^BitsPerPixel items zijn en reserveert de afbeelding meer ruimte voor alle mogelijke paletitems. Het instellen van deze waarde op true en het wijzigen van paletitems kan prestatieverlies veroorzaken omdat gegevensverplaatsing kan optreden, dus gebruik het voorzichtig.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

