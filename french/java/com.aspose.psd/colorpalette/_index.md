---
title: "ColorPalette"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Définit un tableau de couleurs qui composent une palette de couleurs."
type: docs
weight: 27
url: /fr/java/com.aspose.psd/colorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public final class ColorPalette implements IColorPalette
```

Définit un tableau de couleurs qui composent une palette de couleurs. Les couleurs sont des couleurs ARGB 32 bits. Non héritable.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ColorPalette(int[] argb32Entries, boolean isCompactPalette)](#ColorPalette-int---boolean-) | Initialise une nouvelle instance de la classe  ColorPalette . |
| [ColorPalette(int[] argb32Entries)](#ColorPalette-int---) | Initialise une nouvelle instance de la classe  ColorPalette  et IsCompactPalette est false. |
| [ColorPalette(Color[] entries, boolean isCompactPalette)](#ColorPalette-com.aspose.psd.Color---boolean-) | Initialise une nouvelle instance de la classe  ColorPalette . |
| [ColorPalette(Color[] entries)](#ColorPalette-com.aspose.psd.Color---) | Initialise une nouvelle instance de la classe  ColorPalette  et IsCompactPalette est false. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | Copie la palette. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | Copie la palette. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Obtient la couleur de la palette ARGB 32 bits par indice. |
| [getArgb32Entries()](#getArgb32Entries--) | Obtient un tableau de structures ARGB 32 bits. |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | Obtient la couleur de la palette par indice. |
| [getEntries()](#getEntries--) | Obtient un tableau de structures  com.aspose.psd.Color . |
| [getEntriesCount()](#getEntriesCount--) | Obtient le nombre d'entrées. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Obtient l'indice de la couleur la plus proche. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Obtient l'indice de la couleur la plus proche. |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | Obtient ou définit une valeur indiquant si une palette compacte est utilisée. |
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


Initialise une nouvelle instance de la classe  ColorPalette .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| argb32Entries | int[] | Les entrées de la palette de couleurs ARGB 32 bits. |
| isCompactPalette | booléen | Indiquant si la palette est compacte. |

### ColorPalette(int[] argb32Entries) {#ColorPalette-int---}
```
public ColorPalette(int[] argb32Entries)
```


Initialise une nouvelle instance de la classe  ColorPalette  et IsCompactPalette est false.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| argb32Entries | int[] | Les entrées de la palette de couleurs ARGB 32 bits. |

### ColorPalette(Color[] entries, boolean isCompactPalette) {#ColorPalette-com.aspose.psd.Color---boolean-}
```
public ColorPalette(Color[] entries, boolean isCompactPalette)
```


Initialise une nouvelle instance de la classe  ColorPalette .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | Les entrées de la palette de couleurs. |
| isCompactPalette | booléen | Indiquant si la palette est compacte. |

### ColorPalette(Color[] entries) {#ColorPalette-com.aspose.psd.Color---}
```
public ColorPalette(Color[] entries)
```


Initialise une nouvelle instance de la classe  ColorPalette  et IsCompactPalette est false.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | Les entrées de la palette de couleurs. |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette)
```


Copie la palette.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La palette de couleurs. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Copie la palette.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La palette de couleurs. |
| useCompactPalette | booléen | Indiquant si la palette est compacte. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
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
public int getArgb32Color(int index)
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
public int[] getArgb32Entries()
```


Obtient un tableau de structures ARGB 32 bits.

**Returns:**
int[] - Les entrées. Le tableau de structures ARGB 32 bits qui composent cette  Aspose.Imaging.ColorPalette .
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


Obtient la couleur de la palette par indice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index de couleur de la palette. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color palette entry specified by the  index .
### getEntries() {#getEntries--}
```
public Color[] getEntries()
```


Obtient un tableau de structures  com.aspose.psd.Color .

**Returns:**
com.aspose.psd.Color[] - Les entrées. Le tableau de la structure com.aspose.psd.Color qui compose cette Aspose.Imaging.ColorPalette.
### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


Obtient le nombre d'entrées.

**Returns:**
int - Le nombre d'entrées.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public int getNearestColorIndex(Color color)
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
public int getNearestColorIndex(int argb32Color)
```


Obtient l'indice de la couleur la plus proche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| argb32Color | int | La couleur ARGB 32 bits. |

**Returns:**
int - L'index de la couleur la plus proche.
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


Obtient ou définit une valeur indiquant si une palette compacte est utilisée.

**Returns:**
boolean -  true  si une palette compacte est utilisée ; sinon,  false .

Une palette compacte signifie que l'image ne contiendra que les entrées de palette spécifiées si possible, ou en d'autres termes, l'image sera plus compacte et occupera moins d'espace ; sinon, il y aura 2^BitsPerPixel entrées et l'image réservera plus d'espace pour toutes les entrées de palette possibles. Mettre cette valeur à true et modifier les entrées de palette peut entraîner une pénalité de performance puisque des déplacements de données peuvent survenir, utilisez‑le donc avec précaution.
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

