---
title: "Kleurenpalet"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Definieert een array van kleuren die een kleurenpalet vormen."
type: docs
weight: 27
url: /nl/java/com.aspose.psd/colorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public final class ColorPalette implements IColorPalette
```

Definieert een array van kleuren die een kleurenpalet vormen. De kleuren zijn 32-bit ARGB-kleuren. Niet erfbaar.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ColorPalette(int[] argb32Entries, boolean isCompactPalette)](#ColorPalette-int---boolean-) | Initialiseert een nieuw exemplaar van de  ColorPalette  klasse. |
| [ColorPalette(int[] argb32Entries)](#ColorPalette-int---) | Initialiseert een nieuw exemplaar van de  ColorPalette  klasse en IsCompactPalette is false. |
| [ColorPalette(Color[] entries, boolean isCompactPalette)](#ColorPalette-com.aspose.psd.Color---boolean-) | Initialiseert een nieuw exemplaar van de  ColorPalette  klasse. |
| [ColorPalette(Color[] entries)](#ColorPalette-com.aspose.psd.Color---) | Initialiseert een nieuw exemplaar van de  ColorPalette  klasse en IsCompactPalette is false. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | Kopieert de palet. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | Kopieert de palet. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Haalt de 32-bit ARGB-paletkleur op op basis van index. |
| [getArgb32Entries()](#getArgb32Entries--) | Haalt een array op van 32‑bit ARGB‑structuren. |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | Haalt de paletkleur op op basis van index. |
| [getEntries()](#getEntries--) | Haalt een array op van  com.aspose.psd.Color  structuren. |
| [getEntriesCount()](#getEntriesCount--) | Haalt het aantal items op. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Haalt de index van de dichtstbijzijnde kleur op. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Haalt de index van de dichtstbijzijnde kleur op. |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | Haalt op of stelt een waarde in die aangeeft of een compact palet wordt gebruikt. |
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


Initialiseert een nieuw exemplaar van de  ColorPalette  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| argb32Entries | int[] | De 32‑bit ARGB‑kleurenpalet‑items. |
| isCompactPalette | boolean | Geeft aan of het palet compact is. |

### ColorPalette(int[] argb32Entries) {#ColorPalette-int---}
```
public ColorPalette(int[] argb32Entries)
```


Initialiseert een nieuw exemplaar van de  ColorPalette  klasse en IsCompactPalette is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| argb32Entries | int[] | De 32‑bit ARGB‑kleurenpalet‑items. |

### ColorPalette(Color[] entries, boolean isCompactPalette) {#ColorPalette-com.aspose.psd.Color---boolean-}
```
public ColorPalette(Color[] entries, boolean isCompactPalette)
```


Initialiseert een nieuw exemplaar van de  ColorPalette  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | De invoeren van het kleurpalet. |
| isCompactPalette | boolean | Geeft aan of het palet compact is. |

### ColorPalette(Color[] entries) {#ColorPalette-com.aspose.psd.Color---}
```
public ColorPalette(Color[] entries)
```


Initialiseert een nieuw exemplaar van de  ColorPalette  klasse en IsCompactPalette is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | De invoeren van het kleurpalet. |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette)
```


Kopieert de palet.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Het kleurenpalet. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Kopieert de palet.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Het kleurenpalet. |
| useCompactPalette | boolean | Geeft aan of het palet compact is. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
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
public int getArgb32Color(int index)
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
public int[] getArgb32Entries()
```


Haalt een array op van 32‑bit ARGB‑structuren.

**Returns:**
int[] - De items. De array van 32‑bit ARGB‑structuur die dit  Aspose.Imaging.ColorPalette  vormt.
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


Haalt de paletkleur op op basis van index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De paletkleurindex. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color palette entry specified by the  index .
### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


Haalt een array op van  com.aspose.psd.Color  structuren.

**Returns:**
com.aspose.psd.Color[] - De items. De array van  com.aspose.psd.Color  structuur die dit  Aspose.Imaging.ColorPalette  vormt.
### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


Haalt het aantal items op.

**Returns:**
int - Het aantal items.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public int getNearestColorIndex(Color color)
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
public int getNearestColorIndex(int argb32Color)
```


Haalt de index van de dichtstbijzijnde kleur op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| argb32Color | int | De 32-bit ARGB-kleur. |

**Returns:**
int - De index van de dichtstbijzijnde kleur.
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


Haalt op of stelt een waarde in die aangeeft of een compact palet wordt gebruikt.

**Returns:**
boolean -  true  als een compact palet wordt gebruikt; anders,  false .

Een compact palet betekent dat de afbeelding alleen de opgegeven paletitems bevat indien mogelijk, of met andere woorden, de afbeelding compacter is en minder ruimte inneemt; anders zullen er 2^BitsPerPixel items zijn en reserveert de afbeelding meer ruimte voor alle mogelijke paletitems. Het instellen van deze waarde op true en het wijzigen van paletitems kan prestatieverlies veroorzaken omdat gegevensverplaatsing kan optreden, dus gebruik het voorzichtig.
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

