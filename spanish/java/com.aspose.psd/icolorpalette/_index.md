---
title: "IColorPalette"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "La interfaz de paleta de colores."
type: docs
weight: 117
url: /es/java/com.aspose.psd/icolorpalette/
---
```
public interface IColorPalette
```

La interfaz de paleta de colores.
## Métodos

| Método | Descripción |
| --- | --- |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Obtiene el color de la paleta ARGB de 32 bits por índice. |
| [getArgb32Entries()](#getArgb32Entries--) | Obtiene una matriz de estructuras ARGB de 32 bits. |
| [getColor(int index)](#getColor-int-) | Obtiene el color de la paleta por índice. |
| [getEntries()](#getEntries--) | Obtiene una matriz de  com.aspose.psd.Color  estructuras. |
| [getEntriesCount()](#getEntriesCount--) | Obtiene el recuento de entradas. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Obtiene el índice del color más cercano. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Obtiene el índice del color ARGB de 32 bits más cercano. |
| [isCompactPalette()](#isCompactPalette--) | Obtiene un valor que indica si se usa una paleta compacta. |
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public abstract int getArgb32Color(int index)
```


Obtiene el color de la paleta ARGB de 32 bits por índice.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int | El índice de color de la paleta ARGB de 32 bits. |

**Returns:**
int - La entrada de la paleta de colores especificada por el índice.
### getArgb32Entries() {#getArgb32Entries--}
```
public abstract int[] getArgb32Entries()
```


Obtiene una matriz de estructuras ARGB de 32 bits.

**Returns:**
int[] - Las entradas ARGB de 32 bits. La matriz de estructuras ARGB de 32 bits que forman este com.aspose.psd.ColorPalette.
### getColor(int index) {#getColor-int-}
```
public abstract Color getColor(int index)
```


Obtiene el color de la paleta por índice.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int | El índice de color de la paleta. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color palette entry specified by the  index .
### getEntries() {#getEntries--}
```
public abstract Color[] getEntries()
```


Obtiene una matriz de  com.aspose.psd.Color  estructuras.

**Returns:**
com.aspose.psd.Color[] - Las entradas. La matriz de estructuras com.aspose.psd.Color que forman este com.aspose.psd.ColorPalette.
### getEntriesCount() {#getEntriesCount--}
```
public abstract int getEntriesCount()
```


Obtiene el recuento de entradas.

**Returns:**
int - El recuento de entradas.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public abstract int getNearestColorIndex(Color color)
```


Obtiene el índice del color más cercano.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | El color. |

**Returns:**
int - El índice del color más cercano.
### getNearestColorIndex(int argb32Color) {#getNearestColorIndex-int-}
```
public abstract int getNearestColorIndex(int argb32Color)
```


Obtiene el índice del color ARGB de 32 bits más cercano.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| argb32Color | int | El color ARGB de 32 bits. |

**Returns:**
int - El índice del color más cercano.
### isCompactPalette() {#isCompactPalette--}
```
public abstract boolean isCompactPalette()
```


Obtiene un valor que indica si se usa una paleta compacta.

Una paleta compacta significa que la imagen contendrá solo las entradas de paleta especificadas si es posible; en otras palabras, la imagen será más compacta y ocupará menos espacio; de lo contrario, habrá 2^BitsPerPixel entradas y la imagen reservará más espacio para todas las posibles entradas de la paleta. Establecer este valor en true y cambiar las entradas de la paleta puede causar una penalización de rendimiento ya que puede producirse movimiento de datos, así que úselo con cuidado.

**Returns:**
boolean -  true  si se utiliza una paleta compacta; de lo contrario,  false .
