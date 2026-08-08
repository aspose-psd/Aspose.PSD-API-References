---
title: "IColorPalette"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De kleurpaletinterface."
type: docs
weight: 117
url: /nl/java/com.aspose.psd/icolorpalette/
---
```
public interface IColorPalette
```

De kleurpaletinterface.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Haalt de 32-bit ARGB-paletkleur op op basis van index. |
| [getArgb32Entries()](#getArgb32Entries--) | Haalt een array op van 32‑bit ARGB‑structuren. |
| [getColor(int index)](#getColor-int-) | Haalt de paletkleur op op basis van index. |
| [getEntries()](#getEntries--) | Haalt een array op van  com.aspose.psd.Color  structuren. |
| [getEntriesCount()](#getEntriesCount--) | Haalt het aantal items op. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Haalt de index van de dichtstbijzijnde kleur op. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Haalt de index op van de dichtstbijzijnde 32-bit ARGB-kleur. |
| [isCompactPalette()](#isCompactPalette--) | Haalt een waarde op die aangeeft of een compacte palet wordt gebruikt. |
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public abstract int getArgb32Color(int index)
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
public abstract int[] getArgb32Entries()
```


Haalt een array op van 32‑bit ARGB‑structuren.

**Returns:**
int[] - De 32-bit ARGB-items. De array van 32-bit ARGB-structuren die deze  com.aspose.psd.ColorPalette  vormen.
### getColor(int index) {#getColor-int-}
```
public abstract Color getColor(int index)
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
public abstract Color[] getEntries()
```


Haalt een array op van  com.aspose.psd.Color  structuren.

**Returns:**
com.aspose.psd.Color[] - De items. De array van  com.aspose.psd.Color  structuur die deze  com.aspose.psd.ColorPalette  vormen.
### getEntriesCount() {#getEntriesCount--}
```
public abstract int getEntriesCount()
```


Haalt het aantal items op.

**Returns:**
int - Het aantal items.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public abstract int getNearestColorIndex(Color color)
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
public abstract int getNearestColorIndex(int argb32Color)
```


Haalt de index op van de dichtstbijzijnde 32-bit ARGB-kleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| argb32Color | int | De 32-bit ARGB-kleur. |

**Returns:**
int - De index van de dichtstbijzijnde kleur.
### isCompactPalette() {#isCompactPalette--}
```
public abstract boolean isCompactPalette()
```


Haalt een waarde op die aangeeft of een compacte palet wordt gebruikt.

Een compact palet betekent dat de afbeelding alleen de opgegeven paletitems bevat indien mogelijk, of met andere woorden, de afbeelding compacter is en minder ruimte inneemt; anders zullen er 2^BitsPerPixel items zijn en reserveert de afbeelding meer ruimte voor alle mogelijke paletitems. Het instellen van deze waarde op true en het wijzigen van paletitems kan prestatieverlies veroorzaken omdat gegevensverplaatsing kan optreden, dus gebruik het voorzichtig.

**Returns:**
boolean -  true  als een compact palet wordt gebruikt; anders,  false .
