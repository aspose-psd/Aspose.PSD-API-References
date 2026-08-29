---
title: "IColorPalette"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "L'interface de palette de couleurs."
type: docs
weight: 117
url: /fr/java/com.aspose.psd/icolorpalette/
---
```
public interface IColorPalette
```

L'interface de palette de couleurs.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Obtient la couleur de la palette ARGB 32 bits par indice. |
| [getArgb32Entries()](#getArgb32Entries--) | Obtient un tableau de structures ARGB 32 bits. |
| [getColor(int index)](#getColor-int-) | Obtient la couleur de la palette par indice. |
| [getEntries()](#getEntries--) | Obtient un tableau de structures  com.aspose.psd.Color . |
| [getEntriesCount()](#getEntriesCount--) | Obtient le nombre d'entrées. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Obtient l'indice de la couleur la plus proche. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Obtient l'index de la couleur ARGB 32 bits la plus proche. |
| [isCompactPalette()](#isCompactPalette--) | Obtient une valeur indiquant si une palette compacte est utilisée. |
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public abstract int getArgb32Color(int index)
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
public abstract int[] getArgb32Entries()
```


Obtient un tableau de structures ARGB 32 bits.

**Returns:**
int[] - Les entrées ARGB 32 bits. Le tableau de structures ARGB 32 bits qui composent ce com.aspose.psd.ColorPalette.
### getColor(int index) {#getColor-int-}
```
public abstract Color getColor(int index)
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
public abstract Color[] getEntries()
```


Obtient un tableau de structures  com.aspose.psd.Color .

**Returns:**
com.aspose.psd.Color[] - Les entrées. Le tableau de structures com.aspose.psd.Color qui composent ce com.aspose.psd.ColorPalette.
### getEntriesCount() {#getEntriesCount--}
```
public abstract int getEntriesCount()
```


Obtient le nombre d'entrées.

**Returns:**
int - Le nombre d'entrées.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public abstract int getNearestColorIndex(Color color)
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
public abstract int getNearestColorIndex(int argb32Color)
```


Obtient l'index de la couleur ARGB 32 bits la plus proche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| argb32Color | int | La couleur ARGB 32 bits. |

**Returns:**
int - L'index de la couleur la plus proche.
### isCompactPalette() {#isCompactPalette--}
```
public abstract boolean isCompactPalette()
```


Obtient une valeur indiquant si une palette compacte est utilisée.

Une palette compacte signifie que l'image ne contiendra que les entrées de palette spécifiées si possible, ou en d'autres termes, l'image sera plus compacte et occupera moins d'espace ; sinon, il y aura 2^BitsPerPixel entrées et l'image réservera plus d'espace pour toutes les entrées de palette possibles. Mettre cette valeur à true et modifier les entrées de palette peut entraîner une pénalité de performance puisque des déplacements de données peuvent survenir, utilisez‑le donc avec précaution.

**Returns:**
boolean -  true  si une palette compacte est utilisée ; sinon,  false .
