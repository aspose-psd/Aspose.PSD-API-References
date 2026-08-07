---
title: "ColorPalette"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Definiert ein Array von Farben, das eine Farbpalette bildet."
type: docs
weight: 27
url: /de/java/com.aspose.psd/colorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public final class ColorPalette implements IColorPalette
```

Definiert ein Array von Farben, das eine Farbpalette bildet. Die Farben sind 32‑Bit‑ARGB‑Farben. Nicht vererbbar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ColorPalette(int[] argb32Entries, boolean isCompactPalette)](#ColorPalette-int---boolean-) | Initialisiert eine neue Instanz der  ColorPalette  Klasse. |
| [ColorPalette(int[] argb32Entries)](#ColorPalette-int---) | Initialisiert eine neue Instanz der  ColorPalette  Klasse und IsCompactPalette ist false. |
| [ColorPalette(Color[] entries, boolean isCompactPalette)](#ColorPalette-com.aspose.psd.Color---boolean-) | Initialisiert eine neue Instanz der  ColorPalette  Klasse. |
| [ColorPalette(Color[] entries)](#ColorPalette-com.aspose.psd.Color---) | Initialisiert eine neue Instanz der  ColorPalette  Klasse und IsCompactPalette ist false. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | Kopiert die Palette. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | Kopiert die Palette. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Liefert die 32-Bit-ARGB-Palettenfarbe nach Index. |
| [getArgb32Entries()](#getArgb32Entries--) | Gibt ein Array von 32‑Bit‑ARGB‑Strukturen zurück. |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | Liefert die Palettenfarbe nach Index. |
| [getEntries()](#getEntries--) | Gibt ein Array von  com.aspose.psd.Color  Strukturen zurück. |
| [getEntriesCount()](#getEntriesCount--) | Liefert die Anzahl der Einträge. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Liefert den Index der nächsten Farbe. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Liefert den Index der nächsten Farbe. |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | Liest oder setzt einen Wert, der angibt, ob eine kompakte Palette verwendet wird. |
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


Initialisiert eine neue Instanz der  ColorPalette  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| argb32Entries | int[] | Die 32‑Bit‑ARGB‑Farbpalette‑Einträge. |
| isCompactPalette | boolean | Gibt an, ob die Palette kompakt ist. |

### ColorPalette(int[] argb32Entries) {#ColorPalette-int---}
```
public ColorPalette(int[] argb32Entries)
```


Initialisiert eine neue Instanz der  ColorPalette  Klasse und IsCompactPalette ist false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| argb32Entries | int[] | Die 32‑Bit‑ARGB‑Farbpalette‑Einträge. |

### ColorPalette(Color[] entries, boolean isCompactPalette) {#ColorPalette-com.aspose.psd.Color---boolean-}
```
public ColorPalette(Color[] entries, boolean isCompactPalette)
```


Initialisiert eine neue Instanz der  ColorPalette  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | Die Einträge der Farbpalette. |
| isCompactPalette | boolean | Gibt an, ob die Palette kompakt ist. |

### ColorPalette(Color[] entries) {#ColorPalette-com.aspose.psd.Color---}
```
public ColorPalette(Color[] entries)
```


Initialisiert eine neue Instanz der  ColorPalette  Klasse und IsCompactPalette ist false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | Die Einträge der Farbpalette. |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette)
```


Kopiert die Palette.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Die Farbpalette. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Kopiert die Palette.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Die Farbpalette. |
| useCompactPalette | boolean | Gibt an, ob die Palette kompakt ist. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
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
public int getArgb32Color(int index)
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
public int[] getArgb32Entries()
```


Gibt ein Array von 32‑Bit‑ARGB‑Strukturen zurück.

**Returns:**
int[] - Die Einträge. Das Array von 32‑Bit‑ARGB‑Strukturen, das diese  Aspose.Imaging.ColorPalette  bildet.
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


Liefert die Palettenfarbe nach Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Index | int | Der Palette‑Farbindex. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color palette entry specified by the  index .
### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


Gibt ein Array von  com.aspose.psd.Color  Strukturen zurück.

**Returns:**
com.aspose.psd.Color[] - Die Einträge. Das Array von  com.aspose.psd.Color  Strukturen, das diese  Aspose.Imaging.ColorPalette  bildet.
### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


Liefert die Anzahl der Einträge.

**Returns:**
int - Die Anzahl der Einträge.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public int getNearestColorIndex(Color color)
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
public int getNearestColorIndex(int argb32Color)
```


Liefert den Index der nächsten Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| argb32Color | int | Die 32‑Bit‑ARGB‑Farbe. |

**Returns:**
int – Der Index der nächsten Farbe.
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


Liest oder setzt einen Wert, der angibt, ob eine kompakte Palette verwendet wird.

**Returns:**
boolean -  true  wenn eine kompakte Palette verwendet wird; andernfalls  false .

Eine kompakte Palette bedeutet, dass das Bild nur die angegebenen Paletteneinträge enthält, wenn möglich; mit anderen Worten wird das Bild kompakter und belegt weniger Speicherplatz; andernfalls gibt es 2^BitsPerPixel Einträge und das Bild reserviert mehr Speicher für alle möglichen Paletteneinträge. Das Setzen dieses Wertes auf true und das Ändern von Paletteneinträgen kann eine Leistungseinbuße verursachen, da Datenbewegungen auftreten können, daher sollte es vorsichtig verwendet werden.
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

