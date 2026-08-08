---
title: "IPsdColorPalette"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "La paleta de colores pasd"
type: docs
weight: 134
url: /es/java/com.aspose.psd/ipsdcolorpalette/
---

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public interface IPsdColorPalette extends IColorPalette
```

La paleta de colores pasd
## Métodos

| Método | Descripción |
| --- | --- |
| [getRawEntries()](#getRawEntries--) | Obtiene los datos de las entradas crudas de la paleta de colores. |
| [getRawEntriesCount()](#getRawEntriesCount--) | Obtiene el recuento de las entradas crudas de la paleta de colores. |
| [getTransparentColor()](#getTransparentColor--) | Obtiene el color transparente. |
| [getTransparentIndex()](#getTransparentIndex--) | Obtiene el índice del color transparente. |
| [hasTransparentColor()](#hasTransparentColor--) | Obtiene un valor que indica si el color transparente existe. |
### getRawEntries() {#getRawEntries--}
```
public abstract byte[] getRawEntries()
```


Obtiene los datos de las entradas crudas de la paleta de colores.

Valor: Los datos sin procesar de las entradas de la paleta de colores.

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public abstract int getRawEntriesCount()
```


Obtiene el recuento de las entradas crudas de la paleta de colores.

Valor: El recuento sin procesar de las entradas de la paleta de colores.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public abstract Color getTransparentColor()
```


Obtiene el color transparente.

Valor: El color transparente.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public abstract short getTransparentIndex()
```


Obtiene el índice del color transparente.

Valor: El índice del color transparente.

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public abstract boolean hasTransparentColor()
```


Obtiene un valor que indica si el color transparente existe.

Valor:  true  si el color transparente existe; de lo contrario,  false .

**Returns:**
boolean
