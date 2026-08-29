---
title: "PsdColorPalette"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Die PSD-Farbpalette."
type: docs
weight: 13
url: /de/java/com.aspose.psd.fileformats.psd/psdcolorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IPsdColorPalette](../../com.aspose.psd/ipsdcolorpalette)
```
public class PsdColorPalette implements IPsdColorPalette
```

Die PSD-Farbpalette.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PsdColorPalette(IColorPalette colorPalette)](#PsdColorPalette-com.aspose.psd.IColorPalette-) | Initialisiert eine neue Instanz der Klasse [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(IColorPalette colorPalette, short transparentIndex)](#PsdColorPalette-com.aspose.psd.IColorPalette-short-) | Initialisiert eine neue Instanz der Klasse [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)](#PsdColorPalette-byte---boolean-) | Initialisiert eine neue Instanz der Klasse [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(byte[] rawEntriesData)](#PsdColorPalette-byte---) | Initialisiert eine neue Instanz der Klasse [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) und IsCompactPalette ist false. |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-byte---short-boolean-) | Initialisiert eine neue Instanz der Klasse [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex)](#PsdColorPalette-byte---short-) | Initialisiert eine neue Instanz der Klasse [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) und IsCompactPalette ist false. |
| [PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)](#PsdColorPalette-int---boolean-) | Initialisiert eine neue Instanz der Klasse [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---boolean-) | Initialisiert eine neue Instanz der Klasse [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(Color[] colorPaletteEntries)](#PsdColorPalette-com.aspose.psd.Color---) | Initialisiert eine neue Instanz der Klasse [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) und IsCompactPalette ist false. |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---short-boolean-) | Initialisiert eine neue Instanz der Klasse [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)](#PsdColorPalette-com.aspose.psd.Color---short-) | Initialisiert eine neue Instanz der Klasse [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) und IsCompactPalette ist false. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | Kopiert die Palette. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | Kopiert die Palette. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Liefert die 32-Bit-ARGB-Palettenfarbe nach Index. |
| [getArgb32Entries()](#getArgb32Entries--) | Liefert ein Array von 32-Bit-ARGB-Farben. |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | Liefert die Palettenfarbe nach Index. |
| [getEntries()](#getEntries--) | Liefert ein Array von [Color](../../com.aspose.psd/color)-Strukturen. |
| [getEntriesCount()](#getEntriesCount--) | Liefert die Anzahl der Einträge. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Liefert den Index der nächsten Farbe. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Liefert den Index der nächsten Farbe. |
| [getRawEntries()](#getRawEntries--) | Liefert die Rohdaten der Farbpalletten-Einträge. |
| [getRawEntriesCount()](#getRawEntriesCount--) | Liefert die Rohanzahl der Farbpalletten-Einträge. |
| [getTransparentColor()](#getTransparentColor--) | Liefert die transparente Farbe. |
| [getTransparentIndex()](#getTransparentIndex--) | Liefert den Index der transparenten Farbe. |
| [hasTransparentColor()](#hasTransparentColor--) | Ermittelt einen Wert, der angibt, ob eine transparente Farbe vorhanden ist. |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | Ermittelt einen Wert, der angibt, ob die Palette kompakt ist. |
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


Initialisiert eine neue Instanz der Klasse [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Die Farbpalette. |

### PsdColorPalette(IColorPalette colorPalette, short transparentIndex) {#PsdColorPalette-com.aspose.psd.IColorPalette-short-}
```
public PsdColorPalette(IColorPalette colorPalette, short transparentIndex)
```


Initialisiert eine neue Instanz der Klasse [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Die Farbpalette. |
| transparentIndex | short | Der Index der transparenten Farbe. |

### PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette) {#PsdColorPalette-byte---boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)
```


Initialisiert eine neue Instanz der Klasse [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rawEntriesData | byte[] | Die Roh‑Eintragsdaten. |
| isCompactPalette | boolean | Gibt an, ob die Palette kompakt ist. |

### PsdColorPalette(byte[] rawEntriesData) {#PsdColorPalette-byte---}
```
public PsdColorPalette(byte[] rawEntriesData)
```


Initialisiert eine neue Instanz der Klasse [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) und IsCompactPalette ist false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rawEntriesData | byte[] | Die Roh‑Eintragsdaten. |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-byte---short-boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)
```


Initialisiert eine neue Instanz der Klasse [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rawEntriesData | byte[] | Die Roh‑Eintragsdaten. |
| transparentIndex | short | Der Index der transparenten Farbe. Hinweis: Der Index ist nicht der Index der Rohdaten, sondern bezieht sich auf das konvertierte Farbfeld. |
| useCompactPalette | boolean | Gibt an, ob die Palette kompakt ist. |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex) {#PsdColorPalette-byte---short-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex)
```


Initialisiert eine neue Instanz der Klasse [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) und IsCompactPalette ist false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rawEntriesData | byte[] | Die Roh‑Eintragsdaten. |
| transparentIndex | short | Der Index der transparenten Farbe. Hinweis: Der Index ist nicht der Index der Rohdaten, sondern bezieht sich auf das konvertierte Farbfeld. |

### PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette) {#PsdColorPalette-int---boolean-}
```
public PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)
```


Initialisiert eine neue Instanz der Klasse [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorPaletteArgb32Entries | int[] | Die 32‑Bit‑ARGB‑Einträge der Farbpalette. |
| isCompactPalette | boolean | Gibt an, ob die Palette kompakt ist. |

### PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)
```


Initialisiert eine neue Instanz der Klasse [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Die Einträge der Farbpalette. |
| isCompactPalette | boolean | Gibt an, ob die Palette kompakt ist. |

### PsdColorPalette(Color[] colorPaletteEntries) {#PsdColorPalette-com.aspose.psd.Color---}
```
public PsdColorPalette(Color[] colorPaletteEntries)
```


Initialisiert eine neue Instanz der Klasse [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) und IsCompactPalette ist false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Die Einträge der Farbpalette. |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---short-boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)
```


Initialisiert eine neue Instanz der Klasse [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Die Einträge der Farbpalette. |
| transparentIndex | short | Der Index der transparenten Farbe. |
| useCompactPalette | boolean | Gibt an, ob die Palette kompakt ist. |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex) {#PsdColorPalette-com.aspose.psd.Color---short-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)
```


Initialisiert eine neue Instanz der Klasse [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) und IsCompactPalette ist false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Die Einträge der Farbpalette. |
| transparentIndex | short | Der Index der transparenten Farbe. |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette)
```


Kopiert die Palette.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Die Farbpalette. |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Kopiert die Palette.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Die Farbpalette. |
| useCompactPalette | boolean | Gibt an, ob die Palette kompakt ist. |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public final int getArgb32Color(int index)
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
public final int[] getArgb32Entries()
```


Liefert ein Array von 32-Bit-ARGB-Farben.

**Returns:**
int[] – Das Array aus 32‑Bit‑ARGB‑Strukturen, die diese [ColorPalette](../../com.aspose.psd/colorpalette) bilden. Wert: Die Einträge.
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


Liefert die Palettenfarbe nach Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Index | int | Der Palette‑Farbindex. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color palette entry specified by the  index .
### getEntries() {#getEntries--}
```
public final Color[] getEntries()
```


Liefert ein Array von [Color](../../com.aspose.psd/color)-Strukturen.

**Returns:**
com.aspose.psd.Color[] – Das Array aus [Color](../../com.aspose.psd/color)-Strukturen, die diese [ColorPalette](../../com.aspose.psd/colorpalette) bilden. Wert: Die Einträge.
### getEntriesCount() {#getEntriesCount--}
```
public final int getEntriesCount()
```


Liefert die Anzahl der Einträge.

Wert: Die Anzahl der Einträge.

**Returns:**
int
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public final int getNearestColorIndex(Color color)
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
public final int getNearestColorIndex(int argb32Color)
```


Liefert den Index der nächsten Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| argb32Color | int | Die 32‑Bit‑ARGB‑Farbe. |

**Returns:**
int – Der Index der nächsten Farbe.
### getRawEntries() {#getRawEntries--}
```
public final byte[] getRawEntries()
```


Liefert die Rohdaten der Farbpalletten-Einträge.

Wert: Die Rohdaten der Farbpaletteneinträge.

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public final int getRawEntriesCount()
```


Liefert die Rohanzahl der Farbpalletten-Einträge.

Wert: Die Anzahl der Roh‑Farbpaletteneinträge.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public final Color getTransparentColor()
```


Liefert die transparente Farbe.

Wert: Die transparente Farbe.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public final short getTransparentIndex()
```


Liefert den Index der transparenten Farbe.

Wert: Der Index der transparenten Farbe.

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public final boolean hasTransparentColor()
```


Ermittelt einen Wert, der angibt, ob eine transparente Farbe vorhanden ist.

Wert:  true  wenn transparente Farbe existiert; andernfalls  false .

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


Ermittelt einen Wert, der angibt, ob die Palette kompakt ist.

Wert:  true  wenn die Palette kompakt ist; andernfalls  false .

--------------------

Eine kompakte Palette bedeutet, dass das Bild nur die angegebenen Paletteneinträge enthält, wenn möglich; mit anderen Worten wird das Bild kompakter und belegt weniger Speicherplatz; andernfalls gibt es 2^BitsPerPixel Einträge und das Bild reserviert mehr Speicher für alle möglichen Paletteneinträge. Das Setzen dieses Wertes auf true und das Ändern von Paletteneinträgen kann eine Leistungseinbuße verursachen, da Datenbewegungen auftreten können, daher sollte es vorsichtig verwendet werden.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

