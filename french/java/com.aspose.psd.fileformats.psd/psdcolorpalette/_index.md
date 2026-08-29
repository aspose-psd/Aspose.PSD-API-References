---
title: "PsdColorPalette"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "La palette de couleurs PSD."
type: docs
weight: 13
url: /fr/java/com.aspose.psd.fileformats.psd/psdcolorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IPsdColorPalette](../../com.aspose.psd/ipsdcolorpalette)
```
public class PsdColorPalette implements IPsdColorPalette
```

La palette de couleurs PSD.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PsdColorPalette(IColorPalette colorPalette)](#PsdColorPalette-com.aspose.psd.IColorPalette-) | Initialise une nouvelle instance de la classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(IColorPalette colorPalette, short transparentIndex)](#PsdColorPalette-com.aspose.psd.IColorPalette-short-) | Initialise une nouvelle instance de la classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)](#PsdColorPalette-byte---boolean-) | Initialise une nouvelle instance de la classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(byte[] rawEntriesData)](#PsdColorPalette-byte---) | Initialise une nouvelle instance de la classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) et IsCompactPalette est false. |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-byte---short-boolean-) | Initialise une nouvelle instance de la classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex)](#PsdColorPalette-byte---short-) | Initialise une nouvelle instance de la classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) et IsCompactPalette est false. |
| [PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)](#PsdColorPalette-int---boolean-) | Initialise une nouvelle instance de la classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---boolean-) | Initialise une nouvelle instance de la classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(Color[] colorPaletteEntries)](#PsdColorPalette-com.aspose.psd.Color---) | Initialise une nouvelle instance de la classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) et IsCompactPalette est false. |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---short-boolean-) | Initialise une nouvelle instance de la classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)](#PsdColorPalette-com.aspose.psd.Color---short-) | Initialise une nouvelle instance de la classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) et IsCompactPalette est false. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | Copie la palette. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | Copie la palette. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Obtient la couleur de la palette ARGB 32 bits par indice. |
| [getArgb32Entries()](#getArgb32Entries--) | Obtient un tableau de couleurs ARGB 32 bits. |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | Obtient la couleur de la palette par indice. |
| [getEntries()](#getEntries--) | Obtient un tableau de structures [Color](../../com.aspose.psd/color). |
| [getEntriesCount()](#getEntriesCount--) | Obtient le nombre d'entrées. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Obtient l'indice de la couleur la plus proche. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Obtient l'indice de la couleur la plus proche. |
| [getRawEntries()](#getRawEntries--) | Obtient les données brutes des entrées de la palette de couleurs. |
| [getRawEntriesCount()](#getRawEntriesCount--) | Obtient le nombre brut d'entrées de la palette de couleurs. |
| [getTransparentColor()](#getTransparentColor--) | Obtient la couleur transparente. |
| [getTransparentIndex()](#getTransparentIndex--) | Obtient l'indice de la couleur transparente. |
| [hasTransparentColor()](#hasTransparentColor--) | Obtient une valeur indiquant si une couleur transparente existe. |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | Obtient une valeur indiquant si la palette est compacte. |
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


Initialise une nouvelle instance de la classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La palette de couleurs. |

### PsdColorPalette(IColorPalette colorPalette, short transparentIndex) {#PsdColorPalette-com.aspose.psd.IColorPalette-short-}
```
public PsdColorPalette(IColorPalette colorPalette, short transparentIndex)
```


Initialise une nouvelle instance de la classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La palette de couleurs. |
| transparentIndex | short | L'index de couleur transparente. |

### PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette) {#PsdColorPalette-byte---boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)
```


Initialise une nouvelle instance de la classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rawEntriesData | byte[] | Les données des entrées brutes. |
| isCompactPalette | booléen | Indiquant si la palette est compacte. |

### PsdColorPalette(byte[] rawEntriesData) {#PsdColorPalette-byte---}
```
public PsdColorPalette(byte[] rawEntriesData)
```


Initialise une nouvelle instance de la classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) et IsCompactPalette est false.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rawEntriesData | byte[] | Les données des entrées brutes. |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-byte---short-boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)
```


Initialise une nouvelle instance de la classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rawEntriesData | byte[] | Les données des entrées brutes. |
| transparentIndex | short | L'index de couleur transparente. Notez que l'index n'est pas l'index des entrées brutes, il correspond plutôt au tableau de couleurs converties. |
| useCompactPalette | booléen | Indiquant si la palette est compacte. |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex) {#PsdColorPalette-byte---short-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex)
```


Initialise une nouvelle instance de la classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) et IsCompactPalette est false.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rawEntriesData | byte[] | Les données des entrées brutes. |
| transparentIndex | short | L'index de couleur transparente. Notez que l'index n'est pas l'index des entrées brutes, il correspond plutôt au tableau de couleurs converties. |

### PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette) {#PsdColorPalette-int---boolean-}
```
public PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)
```


Initialise une nouvelle instance de la classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorPaletteArgb32Entries | int[] | Les entrées ARGB 32 bits de la palette de couleurs. |
| isCompactPalette | booléen | Indiquant si la palette est compacte. |

### PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)
```


Initialise une nouvelle instance de la classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Les entrées de la palette de couleurs. |
| isCompactPalette | booléen | Indiquant si la palette est compacte. |

### PsdColorPalette(Color[] colorPaletteEntries) {#PsdColorPalette-com.aspose.psd.Color---}
```
public PsdColorPalette(Color[] colorPaletteEntries)
```


Initialise une nouvelle instance de la classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) et IsCompactPalette est false.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Les entrées de la palette de couleurs. |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---short-boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)
```


Initialise une nouvelle instance de la classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Les entrées de la palette de couleurs. |
| transparentIndex | short | L'index de couleur transparente. |
| useCompactPalette | booléen | Indiquant si la palette est compacte. |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex) {#PsdColorPalette-com.aspose.psd.Color---short-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)
```


Initialise une nouvelle instance de la classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) et IsCompactPalette est false.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Les entrées de la palette de couleurs. |
| transparentIndex | short | L'index de couleur transparente. |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette)
```


Copie la palette.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La palette de couleurs. |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Copie la palette.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La palette de couleurs. |
| useCompactPalette | booléen | Indiquant si la palette est compacte. |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public final int getArgb32Color(int index)
```


Obtient la couleur de la palette ARGB 32 bits par indice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index de couleur ARGB 32 bits de la palette. |

**Returns:**
int - L'entrée de la palette de couleurs spécifiée par l'index.
### getArgb32Entries() {#getArgb32Entries--}
```
public final int[] getArgb32Entries()
```


Obtient un tableau de couleurs ARGB 32 bits.

**Returns:**
int[] - Le tableau de structures ARGB 32 bits qui composent ce [ColorPalette](../../com.aspose.psd/colorpalette). Valeur : Les entrées.
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


Obtient la couleur de la palette par indice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index de couleur de la palette. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color palette entry specified by the  index .
### getEntries() {#getEntries--}
```
public final Color[] getEntries()
```


Obtient un tableau de structures [Color](../../com.aspose.psd/color).

**Returns:**
com.aspose.psd.Color[] - Le tableau de structures [Color](../../com.aspose.psd/color) qui composent ce [ColorPalette](../../com.aspose.psd/colorpalette). Valeur : Les entrées.
### getEntriesCount() {#getEntriesCount--}
```
public final int getEntriesCount()
```


Obtient le nombre d'entrées.

Valeur : Le nombre d'entrées.

**Returns:**
int
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public final int getNearestColorIndex(Color color)
```


Obtient l'indice de la couleur la plus proche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | La couleur. |

**Returns:**
int - L'index de la couleur la plus proche.
### getNearestColorIndex(int argb32Color) {#getNearestColorIndex-int-}
```
public final int getNearestColorIndex(int argb32Color)
```


Obtient l'indice de la couleur la plus proche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| argb32Color | int | La couleur ARGB 32 bits. |

**Returns:**
int - L'index de la couleur la plus proche.
### getRawEntries() {#getRawEntries--}
```
public final byte[] getRawEntries()
```


Obtient les données brutes des entrées de la palette de couleurs.

Valeur : Les données brutes des entrées de la palette de couleurs.

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public final int getRawEntriesCount()
```


Obtient le nombre brut d'entrées de la palette de couleurs.

Valeur : Le nombre d'entrées brutes de la palette de couleurs.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public final Color getTransparentColor()
```


Obtient la couleur transparente.

Valeur : La couleur transparente.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public final short getTransparentIndex()
```


Obtient l'indice de la couleur transparente.

Valeur : L'index de la couleur transparente.

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public final boolean hasTransparentColor()
```


Obtient une valeur indiquant si une couleur transparente existe.

Valeur :  true  si une couleur transparente existe ; sinon,  false .

**Returns:**
booléen
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


Obtient une valeur indiquant si la palette est compacte.

Valeur :  true  si la palette est compacte ; sinon,  false .

--------------------

Une palette compacte signifie que l'image ne contiendra que les entrées de palette spécifiées si possible, ou en d'autres termes, l'image sera plus compacte et occupera moins d'espace ; sinon, il y aura 2^BitsPerPixel entrées et l'image réservera plus d'espace pour toutes les entrées de palette possibles. Mettre cette valeur à true et modifier les entrées de palette peut entraîner une pénalité de performance puisque des déplacements de données peuvent survenir, utilisez‑le donc avec précaution.

**Returns:**
booléen
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

