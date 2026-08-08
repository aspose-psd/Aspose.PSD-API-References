---
title: "PsdColorPalette"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "La paleta de colores PSD."
type: docs
weight: 13
url: /es/java/com.aspose.psd.fileformats.psd/psdcolorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IPsdColorPalette](../../com.aspose.psd/ipsdcolorpalette)
```
public class PsdColorPalette implements IPsdColorPalette
```

La paleta de colores PSD.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PsdColorPalette(IColorPalette colorPalette)](#PsdColorPalette-com.aspose.psd.IColorPalette-) | Inicializa una nueva instancia de la clase [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(IColorPalette colorPalette, short transparentIndex)](#PsdColorPalette-com.aspose.psd.IColorPalette-short-) | Inicializa una nueva instancia de la clase [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)](#PsdColorPalette-byte---boolean-) | Inicializa una nueva instancia de la clase [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(byte[] rawEntriesData)](#PsdColorPalette-byte---) | Inicializa una nueva instancia de la clase [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) y IsCompactPalette es false. |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-byte---short-boolean-) | Inicializa una nueva instancia de la clase [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex)](#PsdColorPalette-byte---short-) | Inicializa una nueva instancia de la clase [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) y IsCompactPalette es false. |
| [PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)](#PsdColorPalette-int---boolean-) | Inicializa una nueva instancia de la clase [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---boolean-) | Inicializa una nueva instancia de la clase [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(Color[] colorPaletteEntries)](#PsdColorPalette-com.aspose.psd.Color---) | Inicializa una nueva instancia de la clase [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) y IsCompactPalette es false. |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---short-boolean-) | Inicializa una nueva instancia de la clase [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)](#PsdColorPalette-com.aspose.psd.Color---short-) | Inicializa una nueva instancia de la clase [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) y IsCompactPalette es false. |
## Métodos

| Método | Descripción |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | Copia la paleta. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | Copia la paleta. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Obtiene el color de la paleta ARGB de 32 bits por índice. |
| [getArgb32Entries()](#getArgb32Entries--) | Obtiene una matriz de colores ARGB de 32 bits. |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | Obtiene el color de la paleta por índice. |
| [getEntries()](#getEntries--) | Obtiene una matriz de estructuras [Color](../../com.aspose.psd/color). |
| [getEntriesCount()](#getEntriesCount--) | Obtiene el recuento de entradas. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Obtiene el índice del color más cercano. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Obtiene el índice del color más cercano. |
| [getRawEntries()](#getRawEntries--) | Obtiene los datos de las entradas crudas de la paleta de colores. |
| [getRawEntriesCount()](#getRawEntriesCount--) | Obtiene el recuento de las entradas crudas de la paleta de colores. |
| [getTransparentColor()](#getTransparentColor--) | Obtiene el color transparente. |
| [getTransparentIndex()](#getTransparentIndex--) | Obtiene el índice del color transparente. |
| [hasTransparentColor()](#hasTransparentColor--) | Obtiene un valor que indica si el color transparente existe. |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | Obtiene un valor que indica si la paleta está compacta. |
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


Inicializa una nueva instancia de la clase [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La paleta de colores. |

### PsdColorPalette(IColorPalette colorPalette, short transparentIndex) {#PsdColorPalette-com.aspose.psd.IColorPalette-short-}
```
public PsdColorPalette(IColorPalette colorPalette, short transparentIndex)
```


Inicializa una nueva instancia de la clase [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La paleta de colores. |
| transparentIndex | short | El índice del color transparente. |

### PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette) {#PsdColorPalette-byte---boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)
```


Inicializa una nueva instancia de la clase [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rawEntriesData | byte[] | Los datos de las entradas crudas. |
| isCompactPalette | boolean | Indica si la paleta está compacta. |

### PsdColorPalette(byte[] rawEntriesData) {#PsdColorPalette-byte---}
```
public PsdColorPalette(byte[] rawEntriesData)
```


Inicializa una nueva instancia de la clase [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) y IsCompactPalette es false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rawEntriesData | byte[] | Los datos de las entradas crudas. |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-byte---short-boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)
```


Inicializa una nueva instancia de la clase [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rawEntriesData | byte[] | Los datos de las entradas crudas. |
| transparentIndex | short | El índice del color transparente. Nota: el índice no es el índice de las entradas crudas, sino que es para la matriz de colores convertidos. |
| useCompactPalette | boolean | Indica si la paleta está compacta. |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex) {#PsdColorPalette-byte---short-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex)
```


Inicializa una nueva instancia de la clase [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) y IsCompactPalette es false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rawEntriesData | byte[] | Los datos de las entradas crudas. |
| transparentIndex | short | El índice del color transparente. Nota: el índice no es el índice de las entradas crudas, sino que es para la matriz de colores convertidos. |

### PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette) {#PsdColorPalette-int---boolean-}
```
public PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)
```


Inicializa una nueva instancia de la clase [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorPaletteArgb32Entries | int[] | Las entradas ARGB de 32 bits de la paleta de colores. |
| isCompactPalette | boolean | Indica si la paleta está compacta. |

### PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)
```


Inicializa una nueva instancia de la clase [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Las entradas de la paleta de colores. |
| isCompactPalette | boolean | Indica si la paleta está compacta. |

### PsdColorPalette(Color[] colorPaletteEntries) {#PsdColorPalette-com.aspose.psd.Color---}
```
public PsdColorPalette(Color[] colorPaletteEntries)
```


Inicializa una nueva instancia de la clase [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) y IsCompactPalette es false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Las entradas de la paleta de colores. |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---short-boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)
```


Inicializa una nueva instancia de la clase [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Las entradas de la paleta de colores. |
| transparentIndex | short | El índice del color transparente. |
| useCompactPalette | boolean | Indica si la paleta está compacta. |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex) {#PsdColorPalette-com.aspose.psd.Color---short-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)
```


Inicializa una nueva instancia de la clase [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) y IsCompactPalette es false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Las entradas de la paleta de colores. |
| transparentIndex | short | El índice del color transparente. |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette)
```


Copia la paleta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La paleta de colores. |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Copia la paleta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La paleta de colores. |
| useCompactPalette | boolean | Indica si la paleta está compacta. |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public final int getArgb32Color(int index)
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
public final int[] getArgb32Entries()
```


Obtiene una matriz de colores ARGB de 32 bits.

**Returns:**
int[] - La matriz de estructuras ARGB de 32 bits que forman este [ColorPalette](../../com.aspose.psd/colorpalette). Valor: Las entradas.
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


Obtiene el color de la paleta por índice.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int | El índice de color de la paleta. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color palette entry specified by the  index .
### getEntries() {#getEntries--}
```
public final Color[] getEntries()
```


Obtiene una matriz de estructuras [Color](../../com.aspose.psd/color).

**Returns:**
com.aspose.psd.Color[] - La matriz de estructuras [Color](../../com.aspose.psd/color) que forman este [ColorPalette](../../com.aspose.psd/colorpalette). Valor: Las entradas.
### getEntriesCount() {#getEntriesCount--}
```
public final int getEntriesCount()
```


Obtiene el recuento de entradas.

Valor: El recuento de entradas.

**Returns:**
int
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public final int getNearestColorIndex(Color color)
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
public final int getNearestColorIndex(int argb32Color)
```


Obtiene el índice del color más cercano.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| argb32Color | int | El color ARGB de 32 bits. |

**Returns:**
int - El índice del color más cercano.
### getRawEntries() {#getRawEntries--}
```
public final byte[] getRawEntries()
```


Obtiene los datos de las entradas crudas de la paleta de colores.

Valor: Los datos sin procesar de las entradas de la paleta de colores.

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public final int getRawEntriesCount()
```


Obtiene el recuento de las entradas crudas de la paleta de colores.

Valor: El recuento sin procesar de las entradas de la paleta de colores.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public final Color getTransparentColor()
```


Obtiene el color transparente.

Valor: El color transparente.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public final short getTransparentIndex()
```


Obtiene el índice del color transparente.

Valor: El índice del color transparente.

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public final boolean hasTransparentColor()
```


Obtiene un valor que indica si el color transparente existe.

Valor:  true  si el color transparente existe; de lo contrario,  false .

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


Obtiene un valor que indica si la paleta está compacta.

Valor:  true  si la paleta está compactada; de lo contrario,  false .

--------------------

Una paleta compacta significa que la imagen contendrá solo las entradas de paleta especificadas si es posible; en otras palabras, la imagen será más compacta y ocupará menos espacio; de lo contrario, habrá 2^BitsPerPixel entradas y la imagen reservará más espacio para todas las posibles entradas de la paleta. Establecer este valor en true y cambiar las entradas de la paleta puede causar una penalización de rendimiento ya que puede producirse movimiento de datos, así que úselo con cuidado.

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

