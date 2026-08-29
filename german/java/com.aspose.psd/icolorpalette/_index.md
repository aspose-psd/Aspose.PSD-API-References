---
title: "IColorPalette"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Die Schnittstelle für Farbpaletten."
type: docs
weight: 117
url: /de/java/com.aspose.psd/icolorpalette/
---
```
public interface IColorPalette
```

Die Schnittstelle für Farbpaletten.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Liefert die 32-Bit-ARGB-Palettenfarbe nach Index. |
| [getArgb32Entries()](#getArgb32Entries--) | Gibt ein Array von 32‑Bit‑ARGB‑Strukturen zurück. |
| [getColor(int index)](#getColor-int-) | Liefert die Palettenfarbe nach Index. |
| [getEntries()](#getEntries--) | Gibt ein Array von  com.aspose.psd.Color  Strukturen zurück. |
| [getEntriesCount()](#getEntriesCount--) | Liefert die Anzahl der Einträge. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Liefert den Index der nächsten Farbe. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Liefert den Index der nächstgelegenen 32‑Bit‑ARGB‑Farbe. |
| [isCompactPalette()](#isCompactPalette--) | Liefert einen Wert, der angibt, ob eine kompakte Palette verwendet wird. |
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public abstract int getArgb32Color(int index)
```


Liefert die 32-Bit-ARGB-Palettenfarbe nach Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Index | int | Der 32‑Bit‑ARGB‑Palette‑Farbindex. |

**Returns:**
int – Der Farbpaletteneintrag, der durch den Index angegeben wird.
### getArgb32Entries() {#getArgb32Entries--}
```
public abstract int[] getArgb32Entries()
```


Gibt ein Array von 32‑Bit‑ARGB‑Strukturen zurück.

**Returns:**
int[] - Die 32‑Bit‑ARGB‑Einträge. Das Array der 32‑Bit‑ARGB‑Struktur, die diese com.aspose.psd.ColorPalette bildet.
### getColor(int index) {#getColor-int-}
```
public abstract Color getColor(int index)
```


Liefert die Palettenfarbe nach Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Index | int | Der Palette‑Farbindex. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color palette entry specified by the  index .
### getEntries() {#getEntries--}
```
public abstract Color[] getEntries()
```


Gibt ein Array von  com.aspose.psd.Color  Strukturen zurück.

**Returns:**
com.aspose.psd.Color[] - Die Einträge. Das Array der com.aspose.psd.Color‑Struktur, die diese com.aspose.psd.ColorPalette bildet.
### getEntriesCount() {#getEntriesCount--}
```
public abstract int getEntriesCount()
```


Liefert die Anzahl der Einträge.

**Returns:**
int - Die Anzahl der Einträge.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public abstract int getNearestColorIndex(Color color)
```


Liefert den Index der nächsten Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Die Farbe. |

**Returns:**
int – Der Index der nächsten Farbe.
### getNearestColorIndex(int argb32Color) {#getNearestColorIndex-int-}
```
public abstract int getNearestColorIndex(int argb32Color)
```


Liefert den Index der nächstgelegenen 32‑Bit‑ARGB‑Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| argb32Color | int | Die 32‑Bit‑ARGB‑Farbe. |

**Returns:**
int – Der Index der nächsten Farbe.
### isCompactPalette() {#isCompactPalette--}
```
public abstract boolean isCompactPalette()
```


Liefert einen Wert, der angibt, ob eine kompakte Palette verwendet wird.

Eine kompakte Palette bedeutet, dass das Bild nur die angegebenen Paletteneinträge enthält, wenn möglich; mit anderen Worten wird das Bild kompakter und belegt weniger Speicherplatz; andernfalls gibt es 2^BitsPerPixel Einträge und das Bild reserviert mehr Speicher für alle möglichen Paletteneinträge. Das Setzen dieses Wertes auf true und das Ändern von Paletteneinträgen kann eine Leistungseinbuße verursachen, da Datenbewegungen auftreten können, daher sollte es vorsichtig verwendet werden.

**Returns:**
boolean -  true  wenn eine kompakte Palette verwendet wird; andernfalls  false .
