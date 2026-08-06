---
title: "IPsdColorPalette"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "La palette de couleurs pasd"
type: docs
weight: 134
url: /fr/java/com.aspose.psd/ipsdcolorpalette/
---

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public interface IPsdColorPalette extends IColorPalette
```

La palette de couleurs pasd
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRawEntries()](#getRawEntries--) | Obtient les données brutes des entrées de la palette de couleurs. |
| [getRawEntriesCount()](#getRawEntriesCount--) | Obtient le nombre brut d'entrées de la palette de couleurs. |
| [getTransparentColor()](#getTransparentColor--) | Obtient la couleur transparente. |
| [getTransparentIndex()](#getTransparentIndex--) | Obtient l'indice de la couleur transparente. |
| [hasTransparentColor()](#hasTransparentColor--) | Obtient une valeur indiquant si une couleur transparente existe. |
### getRawEntries() {#getRawEntries--}
```
public abstract byte[] getRawEntries()
```


Obtient les données brutes des entrées de la palette de couleurs.

Valeur : Les données brutes des entrées de la palette de couleurs.

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public abstract int getRawEntriesCount()
```


Obtient le nombre brut d'entrées de la palette de couleurs.

Valeur : Le nombre d'entrées brutes de la palette de couleurs.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public abstract Color getTransparentColor()
```


Obtient la couleur transparente.

Valeur : La couleur transparente.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public abstract short getTransparentIndex()
```


Obtient l'indice de la couleur transparente.

Valeur : L'index de la couleur transparente.

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public abstract boolean hasTransparentColor()
```


Obtient une valeur indiquant si une couleur transparente existe.

Valeur :  true  si une couleur transparente existe ; sinon,  false .

**Returns:**
booléen
